# Style Guide (Yearn)

The Yearn Community Writing Style Guide summarizes the standards and best practices writers should follow when contributing to Yearn Documentation resources.

## Writing Intent and Tone <a href="writing-intent-and-tone" id="writing-intent-and-tone"></a>

Yearn Community materials should cater to readers who are unfamiliar with the Yearn ecosystem. Writers should also assume that their readers have tight schedules and short attention spans, as after all, farming is honest but hard work.As such, Writers should focus on communicating concepts as clearly and succinctly as possible.

* Use simple language.Use short, concise sentences.Avoid unnecessary words.Remain open and objective.Provide examples when possible.Provide examples to help explain concepts, but avoid overcomplicating them.
*
  * Use math when necessary, but keep it simple and visually easy to understand.
* Link to basic terms if necessary.

## Writer Guidelines <a href="writer-guidelines" id="writer-guidelines"></a>

### General Rules <a href="general-rules" id="general-rules"></a>

* Run all drafts through [Grammarly](https://app.grammarly.com) regularly, and before final submissions.
*
  * Grammarly will catch most spelling and grammatical errors.Copy rendered text into Grammarly and address any mistakes it flags.
  *
    * HackMD does not identify spelling and grammatical errors.Grammarly will miss errors if it’s given raw Markdown text.Be careful of copy and pasting code from Grammarly to VScode, Grammarly may mess with formatting.

Please Note

* When migrating to a new document (i.e., from Google Docs to HackMD):
*
  * Leave a note in the old file.Provide a link to the latest version.
* Do not blindly accept Grammarly suggestions.
*
  * Review edits to make sure they make sense.

Use:

* ​[Oxford commas](https://en.wikipedia.org/wiki/Serial\_comma).​[Pluralized, gender-neutral pronouns](https://en.wikipedia.org/wiki/Singular\_they).
*
  * Use “they/their” instead of “he/she/his/hers.”Examples: “When they…” or “If users choose to X, then their…”
* The % symbol. Do not spell out "percent."
*
  * Correct: 15%Incorrect: 15 percent
* Double quotes " " for phrases, quotes, etc.
*
  * Do not use single ' ' quotes.

Avoid:

* ​[First-person language.](https://en.wikipedia.org/wiki/Grammatical\_person)​
*
  * Examples: I, we, our, etc.
* ​[Second-person language](https://en.wikipedia.org/wiki/Grammatical\_person) (unless it is appropriate for a guide or action page).
*
  * Examples: "You then..." or "Now you should..."
* Exclamation points.Footnotes.References to deprecated names for Yearn Components.
*
  * Examples: yyCRV or yUSD instead of yvCurve-Y (see: [Yearn Naming Conventions](https://github.com/yearn/yearn-docs/tree/43e3fe86ebcdd9f47efd3b7f481f168f5e289e4b/contributors/developers/naming-convention.md)).
* Parentheses for stating additional information.
*
  * Incorrect: Development Grants are larger sized ($5,000 to $50,000) grants aimed at individuals or teams building projects around vaults and the broader Yearn ecosystem.Correct: Development Grants are generally larger sized grants, ranging from $5,000 to $50,000, aimed at individuals or teams building projects around vaults and the broader Yearn ecosystem.

### Abbreviations <a href="abbreviations" id="abbreviations"></a>

* Use parentheses to define abbreviated terms the first time they appear in a given document.
*
  * Example: A Yearn Improvement Proposal (YIP) is a proposal framework to support new initiatives and to expand the scope of existing ones.

### Acronyms, Decades and Cases <a href="acronyms-decades-and-cases" id="acronyms-decades-and-cases"></a>

Do not use apostrophes to pluralize acronyms or indicate decades. Add an "s" at the end.

#### Acronyms <a href="acronyms" id="acronyms"></a>

* To make an acronym plural:
*
  * Correct: YIPsIncorrect: YIP's

#### Decades <a href="decades" id="decades"></a>

* To indicate a decade:
*
  * Correct: 1990sIncorrect: 1990's

#### Capitalize <a href="capitalize" id="capitalize"></a>

* Names and proper nouns.Cities, countries, nationalities, and languages.Terms with definitions provided by Yearn.

#### Title Case <a href="title-case" id="title-case"></a>

* The [Title Case Converter](https://titlecaseconverter.com) will keep titles consistent.Follow the New York Times standard.Capitalize the first and last words, all nouns, pronouns, verbs, adverbs, and adjectives.Lowercase all articles, conjunctions, and prepositions.

### Currencies <a href="currencies" id="currencies"></a>

The examples below use dollars, but the same rules apply to all global currencies.

* Use lowercase except when writing "US Dollar.”Use figures and the "$" sign in all except casual references, or amounts without a figure.
*
  * Standard: "The book costs $4."Casual: "Please give me a dollar."
* For amounts under $1 million, follow this format:
*
  * Correct: $4, $25, $500, $1,000, $650,000.
* For amounts over $1 million, use the word, not numerals.
*
  * Correct: "He is worth $4 million."Incorrect: "He is worth $4,000,000."

### Naming Conventions <a href="naming-conventions" id="naming-conventions"></a>

#### Cryptocurrencies <a href="cryptocurrencies" id="cryptocurrencies"></a>

* When directly referring to the creation, destruction, or manipulation of a token (particularly as it relates to tooling) or when referencing the token as a currency, in an instructional or conversational setting, or as a conceptual product of the Foundation or its systems:
*
  * Use the proper prefix if necessary and capitalized TLA version: wETHExample: “wETH is a token that represents Ether 1:1 and conforms to the ERC20 token standard.”
* Similarly, when referring to exchange pairs:
*
  * Use: wETH/DAI

#### Yearn Products <a href="yearn-products" id="yearn-products"></a>

Please see [Yearn Naming Conventions](https://github.com/yearn/yearn-docs/tree/43e3fe86ebcdd9f47efd3b7f481f168f5e289e4b/contributors/developers/naming-convention.md).

#### Yearn <a href="yearn" id="yearn"></a>

* When referring to Yearn as a smart contract system, use "The Yearn Protocol."
*
  * Example: “The Yearn Protocol is a set of contracts for yield optimization."
* When referring to Yearn as a body of YFI voters and the general stakeholder community, use "Yearn Community" or simply "Yearn."
*
  * Example: "Yearn passed a vote to decrease the yCRV vault performance fee."Example: "The Yearn Community passed a vote to add an additional vault."
* Use "Yearn" for casual references to Yearn and the Yearn Protocol as a whole.

### Numbers <a href="numbers" id="numbers"></a>

* Spell out numbers below 10.
*
  * Examples: one, two, three, etc.
* Use numerals for numbers above 10, unless starting a sentence.For numbers with million, billion, or trillion, use figures in all except casual cases.
*
  * Standard: "The nation has 1 million citizens."Casual: "I'd like to make a billion dollars."

### Lists <a href="lists" id="lists"></a>

When bulleted and numbered lists contain complete sentences, capitalize the first word, and follow each with a period. If list items are phrases, no capitalization or punctuation is required.

* Don't use a list with only 1 item.Use [parallel construction](https://en.wikipedia.org/wiki/Parallelism\_\(grammar\)) for each item in a list.Start with the same [part of speech](https://en.wikipedia.org/wiki/Part\_of\_speech) for each item (in this case, a verb).Use the same verb [tense](https://en.wikipedia.org/wiki/Grammatical\_tense#English) for each item.Use the same [voice](https://en.wikipedia.org/wiki/Voice\_\(grammar\)) for each item.Use the same sentence type (statement, question, exclamation) for each item.List items that include definitions should look like this:
*
  * Team: Yearn Protocol Developers and ContributorsCommunity: General participants in Yearn forums and chat
* Use dashes rather than asterisks for unordered lists.
*
  * Correct: -Incorrect: \*
* Alphabetize lists of names unless there is a clear priority at work.Do not use ordered (numbered) lists unless order matters.Ordered list items should use the 1. repeated.
*
  * Markdown will automatically generate numbers.

Example:11. Item 121. Item 231. Item 341. Item 3a51. Item 3bCopied!

### Links <a href="links" id="links"></a>

* Use [absolute links](https://docs.microsoft.com/en-us/contribute/how-to-write-links) and standard web URLs when referencing external resources.Create descriptive hyperlinks and avoid generic language.
*
  * Correct - Descriptive: (Learn more at [Yearn Documentation](https://docs.yearn.finance)​Incorrect - Generic: Learn more [here](https://docs.yearn.finance).
* Include a .outside the link for sentences that end with a link.When creating links for parallel translated documents, make sure to update relative links to reflect the correct heading.

### Tables of Contents <a href="tables-of-contents" id="tables-of-contents"></a>

* Include a table of contents for documents that span several pages and multiple sections.Use the raw Markdown from the Table of Contents above as a template.
*
  * Be sure to include the line breaks --- as well to keep formatting consistent.
* The table of contents should list relevant sections for easy navigation.

## Markdown Guide <a href="markdown-guide" id="markdown-guide"></a>

Yearn documents posted on GitHub are written in Markdown, a text-to-HTML conversion tool for web writers.

* Include line breaks above and below headings.Use top-level headers (#) only once per document.
*
  * Do not make multiple top-level headings.
* Avoid repeat headings.
*
  * They will break auto-generated navigation.
* Avoid trailing spaces.Do not use:
*
  * Em or en [dashes:](https://en.wikipedia.org/wiki/Wikipedia:Hyphens\_and\_dashes) —Ampersands & in titles and headers.Pipes | in titles and headers.Curly quotes. Use the plaintext version.
  *
    * Correct: "Incorrect: “
  * Escaping parentheses. Use normal parentheses.
  *
    * Correct: (SOMETHING)Incorrect: \\(SOMETHING\\)
* Ensure there is a single hard return at the end of a .md file.Use emojis to call attention to an important point, when necessary.
*
  * Practice discretion and use them sparingly.This [cheat sheet](https://gist.github.com/rxaviers/7360908) lists emojis and their Markdown shortcuts.

## Best Practices and Resources <a href="best-practices-and-resources" id="best-practices-and-resources"></a>

Writers and contributors familiar with Yearn and cryptocurrency basics will have a better sense of where to apply their skills best.

* Spend some time learning about Yearn's function, history, and any recent events before contributing.In-depth knowledge is appreciated but not required.

### Learn the Basics of Markdown <a href="learn-the-basics-of-markdown" id="learn-the-basics-of-markdown"></a>

* ​[Daring Fireball](https://daringfireball.net/projects/markdown/)​​[Markdown Syntax Guide](https://guides.github.com/features/mastering-markdown/)​​[Practice Communicating Using Markdown](https://lab.github.com/githubtraining/communicating-using-markdown)​

### Helpful Writing Tools <a href="helpful-writing-tools" id="helpful-writing-tools"></a>

Make use of any writing tools that help improve workflow and writing quality. See the list below for some recommendations.

#### Text Editors <a href="text-editors" id="text-editors"></a>

* ​[Grammarly](https://app.grammarly.com) - Mistake-free writing editor​[HemingwayApp](https://www.hemingwayapp.com) - Make writing bold and clear

#### Word Choice <a href="word-choice" id="word-choice"></a>

* ​[Thesaurus](https://www.thesaurus.com) - Synonyms​[Powerthesaurus](https://www.powerthesaurus.org) - Synonyms and phrase suggestions​[WordHippo](https://www.wordhippo.com) - Synonyms and phrase suggestions

### Review Community Guides <a href="review-community-guides" id="review-community-guides"></a>

Review the respective Contribute.md for each repository where pertinent before starting work on any Yearn project.

* Yearn contributor guides outline writing standards and help simplify the writing process.

#### Document-Specific Maintenance Guides <a href="document-specific-maintenance-guides" id="document-specific-maintenance-guides"></a>

* Check for an associated maintenance guide before starting work on a given document if applicable.A document maintenance guide outlines standards to help Reviewers and contributors when maintaining a given resource.
*
  * The rules described within a document-specific maintenance guide supersede other guides.If a discrepancy is glaring or unreasonable, bring the issue to an admin in the [#documentation](https://discord.com/channels/734804446353031319/748476302121762866) channel on Yearn's discord.

#### Contributor Tools <a href="contributor-tools" id="contributor-tools"></a>

* The [Contributor Tools Guide](https://github.com/yearn/yearn-docs/tree/43e3fe86ebcdd9f47efd3b7f481f168f5e289e4b/contributors/documentation/contributor-tools.md) guide introduces the tools regularly used by Yearn contributors.

### Express Interest <a href="express-interest" id="express-interest"></a>

* Check out the [Getting Started guide](https://docs.yearn.finance/contributors/documentation/writing-style-guide) for contributing to Documentation.Join the [#documentation](https://discord.com/channels/734804446353031319/748476302121762866) channel on Yearn's Discord, read the pinned messages, and reach out to a channel admin.Yearn community team members and senior contributors help onboard new contributors via Discord or Telegram chats where applicable.Feel free to discuss personal interests and relevant skills to help determine a well-suited project/issue and jump right in.To understand strengths you can also provide relevant examples of past projects, work, and experience.
*
  * Demonstrate a reliable work ethic and offer quality work that speaks for itself.Stand out by suggesting projects and adding insight to public discussions.

### Collaborate <a href="collaborate" id="collaborate"></a>

* When accepting an assignment, be sure to collaborate early and often.Visit [#documentation](https://discord.com/channels/734804446353031319/748476302121762866) or corresponding Telegram chat regularly.Coordinate with other members.
*
  * Ask as many questions as necessaryAsk for feedback when stuck.Provide frequent progress updates.
* Develop a plan that defines an approach for an assignment.
*
  * Produce a project outline. Clarify the what so we can agree on the how.Set achievable deadlines. Timeboxing is good :)Assign and divide tasks with other contributors.
  *
    * Multiple contributors should not start work on similar projects individually. Please check that the same issue does not already exist in the Github Issues for that Repository, and if it does please coordinate with whoever is working on it to divide the work if needed.

#### Track Progress <a href="track-progress" id="track-progress"></a>

* Track projects and progress with [GitHub Issues.](https://github.com/orgs/yearn/projects/2)​
*
  * Keep GitHub issues updated with comments and feedback.
* Take advantage of version history when working in HackMD or Google Docs.

#### Final Drafts and Submissions <a href="final-drafts-and-submissions" id="final-drafts-and-submissions"></a>

* Transfer approved final drafts from Google Docs to HackMD or DrawIO(for diagrams) if need be.Let the team know when a project is ready for final review by moving your issue to the status of Pending Review on Github and messaging in the appropriate Discord or Telegram channel.Once reviewed, submit completed projects for approval as a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) on GitHub.
*
  * Ensure to update any relevant issues and the project board on GitHub

### Acknowledgements <a href="acknowledgements" id="acknowledgements"></a>

This document could not be possible without the amazing work done by the MakerDAO team as this document is mostly based on their [Writing Style Guide](https://github.com/makerdao/community-portal/blob/r2d/content/en/contribute/content/writing-style-guide.mdx).
