# Proposal Types - Advanced



In the Moloch v2 smart contracts, there are 8 proposal types which must pass a voting and grace period, similar to Moloch v1, including:

* Membership admission proposals: A successful membership proposal admits a new member into the DAO through the issuance of DAO shares. These DAO shares, provide members governance rights and a claim of the assets under the GuildBank's management. The flow for membership proposals is as follows:
* A DAO membership applicant's tribute funds are escrowed in the Moloch.sol smart contract as their membership proposal passes through voting and grace periods
* When the DAO proposal passes, the DAO membership tribute funds are moved from Moloch.sol into the GuildBank, where a non-transferable membership interest will be minted and assigned to the newly approved DAO member. 
* "Membership" proposals can also offer cryptonative tokens (instead of shares) as payment. Legally speaking, these are not membership proposals but simply a mechanic for receiving payment from the DAO for some property or service.
* Membership expulsion (GuildKick) proposals: Any member may at any time propose that another member (the 'target member') be expelled from the DAO by submitting a guildKickProposal. If that proposal is approved by sufficient other members, then one of two events will occur:
* Possibility #1: If the member has not voted previously voted "YES" on any proposal that is still pending (eg. being voted on or already approved but in the grace period), then the target member will immediately be rageQuitted with the same effect as if the target member had rageQuitted voluntarily (eg. member receives all RageTokens and RageClaims, pro rata).
* Possibility #2: If the member has voted "YES" on any proposal that is still pending (eg. being voted on or already approved but in the grace period), the member cannot be force-rageQuitted immediately (for the same reason that we do not allow members to voluntarily rageQuit in the same circumstance), therefore, the member is "jailed".
* Jailing & Ragekick: In the case that a member has been the target of a GuildKick, but have previously voted "YES" on pending proposals, they are not allowed to immediately RageQuit the DAO. Just as if this were a voluntary RageQuit, they are "Jailed" and held in the DAO with "loot" (non-voting shares) temporarily with a maximum sentence of two weeks for proposals to pass and to ensure that the target member remain responsible for the effects of the proposals they have voted "YES" on.
* Until the proposals that the Jailed member voted "YES" on are processed, they are Jailed and cannot vote upon any other proposals. Essentially, the GuildKicked member is no longer a full member, but is stuck holding a pure economic claim to the relevant RageTokens and RageClaims for a period of time before it actually receives the distribution. 
* Once all of the relevant pending proposals have been fully processed, any member can call the "RageKick" function on the target member, or the Jailed member can call the "RageQuit" function on themselves. Either action will trigger the appropriate distribution of RageTokens and RageClaims to the target member. 
* In the unlikely, but possible event that the target member is blacklisted from receiving a particular RageToken (as in the hypothetical explored above under "RageQuits") and does not "safeRageQuit" soon enough (within 2 weeks), the target member will require a "bailout".
* Bailouts: Bailouts are a failsafe mechanism intended to allow a custodian to facilitate the exit of a member when the funds become stuck in the DAO due to a glitch caused by the third-party smart contract governing one or more RageTokens.
* In a guildKicked member has been sitting in jail for too long (more than two weeks), their "YES" approved proposals were processed, and haven't SafeRageQuitted, they may be bailed out.  This means their funds are "bailed out" to a multisig smart contract controlled by a group of trusted members and/or summoners, who act much like receivers or trustees in a legal proceeding. The Grimoire (along with basic courtesy) will require that this trusted group work to distribute the RageTokens and RageClaims to the exiting member.
* Token whitelist proposals: A successful whitelist proposal which adds a new ERC-20 token address to the token whitelist. These proposals determine what tokens the DAO can manage, invest and take membership tribute in. It is critically important that the smart contracts of tokens proposed to the whitelist are carefully scrutinized for potential transfer restrictions that may cause them to hinder or halt the operation of the DAO.
* Investment proposals: A proposal that transfers funds based on the DAO's agreement to enter into an investment contract. In this case, the DAO receives a whitelisted token in return for the payment to a specified address in the form of shares, a whitelisted token, or any combination.
* OTC/Trade proposals: A proposal that offers tribute and receives payment in another token for the purposes of asset management.
* Grant proposals: A purely output proposal detailing the payment in the form of shares, a whitelisted token, or any combination thereof to a specified address.