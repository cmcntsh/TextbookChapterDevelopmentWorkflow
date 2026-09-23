# Textbook Chapter Development Workflow

This workflow was conducted using ChatGPT Work Desktop. This allows ChatGPT to access designated folders on the computer and access files in those folders. ChatGPT doesn't work well with cloud drives. It's best to use folders directly on your computer. ChatGPT seemed to work with subfolders to keep categories of items separated and organized. I've also tried this with ChatGPT online with good results. (The online version can't access folders on your computer, so you need to upload relevant files.)

## Targeted Literature Search

When you need to find some sources quickly, ChatGPT seems to be improving at finding relevant items.

Prompt: finding evidence (I tried the same question on scite.ai. The sources returned by ChatGPT were far superior. Scite just seemed to take the first things it found.

```
What authoritative texts or peer-reviewed scholarly articles explain <question to answer>? For the sources you list, please provide full APA references, including identifiers such as DOIs or ISBNs or URLs.
```

I went and retrieved the sources identified and saved the references in Zotero. Once I had all my literature sources in the right folder, I ran the next prompt to review each source and extract relevant quotes with citations.

Prompt: Create RIS (.ris) file to import the sources into a citation manager.

```
Please create an RIS (.ris) file that includes all the sources you listed so I can download the file and impoort the references into Zotero.
```

## Identify Relevant Passages

Prompt: create a relevant quote outline from the sources included in the review

```
Please review each source in the <folder name> folder individually. What passages in the source are relevant to the question, "<question>"? For each relevant passage, quote the entire passage without truncation including the APA citation with page numbers for the quote. For each quote, paraphrase what the quote says related to the question and include the APA citation with the page numbers with the paraphrase. For each source, synthesize the paraphrases into a bulleted list with each bullet point listing a main point the source makes about the question stated as a complete sentence. For each sentence in the list, include the APA citation with the relevant page numbers for the paraphrases that support that statement. If a source doesn't contain any passages relevant to the question, state there are no relevant passages. Please list the question addressed by the passages at the top of the outline. Please save this source quotation outline as a markdown file.
```

(Depricated) Prompt: evidence review for relevant passages

```
Please review each article in the <folder name> folder individually. What does the article say that addresses the question, "<question>"? For each sentence you write, please identify full quotes from the article with APA citations, including page numbers from the article, that support your statements. Please add an APA citation with the relevant page numbers to each sentence of your summary of what the article says that addresses the question. If there are passages on multiple pages that support a sentence, please indicate which passage is most important or that provides the strongest support for the sentence.
```

## Agreement, Disagreement, Pattern Analysis

Prompt: analyze the relevant passages and create an outline of the analysis while retaining citation links to the original sources

```
Please create an outline that organizes statements from the source syntheses into the following categories: areas of agreement between the sources regarding the answer to the question; areas of disagreement between the sources regarding the answer to the question; and additional insights, patterns, themes, subgroups, and subtleties from the sources that produce a more comprehensive understanding of the big picture surrounding the question. Please organize the syntheses statements with the APA citations that you extracted from the individual articles above as supporting points for the statements you make for each section in the outline. Finally, create an overall analysis section that evaluates how well the question has been answered by the sources, what gaps may exist in the answer to the question provided by the sources, and any other relevant observations. Please include a complete APA References section at the end. I want to save the outline as a markdown document.
```

(Depricated) Prompt: analyze the relevant passages and create an outline of the analysis while retaining citation links to the original sources

```
Please create an outline that organizes information from the individual articles into the following sections: areas of agreement between the articles regarding the answer to the question; areas of disagreement between the articles regarding the answer to the question; and additional insights, patterns, themes, subgroups, and subtleties from the articles that produce a more comprehensive understanding of the big picture surrounding the question. Please organize the quotations with the APA citations that you extracted from the individual articles above as supporting points for the statements you make for each section in the outline. Finally, create an overall analysis section that evaluates how well the question has been answered by the sources, what gaps may exist in the answer to the question provided by the sources, and any other relevant observations.
```

## Group Analysis Points by Topic

Prompt: create a topical grouping outline from the analysis outline

```
Please reorganize the information from the analysis outline into a topical grouping outline. For each main topic, please list the items from the analysis outline relevant to that topic. Keep the same groupings under the topic heading that were used in the analysis outline (Areas of Agreement; Areas of Disagreement; Additional Insights, Patterns, Themes, Subgroups, and Subtleties; Overall Analysis). 
```

## Get an Ouline of Suggested Synthesis Report Organization

At this point, it may be beneficial to review the outlines already created and get an idea of what you may be looking for when synthesizing the information. In the next prompt, I asked ChatGPT to outline an organizational structure to write up the synthesis. I ended up not liking the recommended structure as much as what I had originally envisioned after reviewing the previous outlines. After the prompt where I asked for a recommendation, I'll also include the prompt where I told ChatGPT to use another structure instead.

Prompt: get a chapter outline suggestion based on the analysis information

```
I need to turn this information into a chapter in a nursing statistics textbook. The chapter needs to inform graduate nursing students why it is important for them to learn about statistics. I need to stick to main points and not dive into less important detail or controversies. Can you suggest a way to organize this information into logical main groupings and ordering for those groupings so the chapter has good flow? What main headings do you suggest and what is your rational for the headings and the order you suggest? Do you think any of the main heading sections need any subsections? Please suggest a paragraph structure for each heading. I'm just trying to think about organization before doing any actual writing, so outline format will be useful.
```

Prompt: ask ChatGPT to work with an organizational structure I suggest

```
I want to stay high-level in this chapter. I want there to be an introduction section at the beginning and a conclusion section at the end. In the middle sections, I'd like there to be main sections for 1) <headings from outline I wanted clustered>; 2) <next cluster heading>; 3) <next cluster heading>; 4) <next cluster heading>; and 5) <final cluster heading>. Please suggest the section headings, purpose, subsection headings (if any), and suggested paragraphs like you did in your previous response, but under this organizational structure.
```

I tried having it adjust some language based on a chapter style guide I developed. I ended up not liking the changes, so I had it revert to the previous version before the changes. I'll include the prompts to document the workflow.

Prompt: change language based on a style guide

```
I have added a <name of style guide file> document to the project folder. I want to keep this Proposed chapter organization as you currently have it, but I would like you to adjust the language to reflect the broader scope of competency levels reflected in the style guide. Your proposed chapter organization will be for the main section of the chapter. I don't want to work on the opener or closer sections yet. Please just keep the main organization of your current proposed chapter organization, but just adjust the language to align with the spirit and tone reflected in the style guide.
```

Prompt: don't use the changes that were made

```
I've decided that I don't want to use the E A P organization strategy for this chapter. I like your original heading, subheading, and chapter suggestions using the 5 sections better. Please just revise the language in your suggestion so it's not just geared toward graduate nurses.
```

## Incorporate Evidence Statements Into Outline

Prompt: add evidence statements to the outline with the proposed paragraphs

```
Please integrate the information from the original outlines into this chapter organization outline. Don't write finished paragraphs yet. Just outline each of your proposed paragraphs with the statements and evidence from the original documents. Please keep the appropriate citations with each line you list for each paragraph. Where appropriate, please suggest ways to synthesize the information from the original outlines to make the chapter insightful. When creating synthesis statements, retain the citations to original sources so original thoughts can be traced back to their origins. Don't integrate the recommended recurring chapter features into the outline yet. I want to focus on the narrative flow of the information presentation before considering the specific elements suggested in the Recommended recurring chapter features section. Please save this new outline as a markdown file. I want to review the chapter organization complete with cited evidence before doing any finished writing.
```

(Depricated) Prompt: add actual evidence to the outline with the proposed paragraphs

```
Please add the explanation and evidence from the original outlines to this chapter organization outline. Don't write finished paragraphs yet. Just outline each of your proposed paragraphs with the statements and evidence from the original documents. Please keep the appropriate citations with each line you list for each paragraph. I want to review the chapter organization complete with cited evidence before doing any finished writing.
```

## Write a Draft Based on the Outline

Prompt: write the chapter text based on the outline

```
Please go ahead and write a draft of the chapter. Please cite sources where appropriate and retain the page numbers in the citations for this draft.
```

I liked the logic and flow of the text that was produced, but the citations didn't make it through the process very well. There ended up being citations on the last sentence of each paragraph only. I decided to have it compare each sentence in the draft to the original passage extraction outline, and put relevant citations where they seemed to belong. This seemed to work well. I've spot checked some, and the citations led back to the correct sources for the citations I checked.

Prompt: compare the draft with the original passage extraction outline and add citations to sentences in the draft where they seemed appropriate

```
Please compare each clause and sentence in the draft of the main body chapter with the original article review quotations. If any clause or sentence reflects what is said in a quotation in that document, please add the citation from that quotation to the clause or sentence in the draft of the main body chapter.
```

That seemed to work well. However, ChatGPT didn't create a new markdown file for the updated draft with corrected citations. I don't want it to overwrite previous work. I needed it to cut the length down. I asked ChatGPT to create a new file for the new shortened draft.

```
I want to keep this draft for future reference. Please create a new draft of this document in a separate file. Please keep the same main headings and subheadings. Please reduce the length of the new draft by about half.
```

Prompt: create the chapter opener

```
Please create a new file for the next draft. Please review the Comprehensive_Textbook_Chapter_Writing_and_Design_Style_Guide.md document and create the Chapter Opener items.
```

Prompt: create the chapter closer

```
Please create a new file for the next draft. Please review the Comprehensive_Textbook_Chapter_Writing_and_Design_Style_Guide.md document and create the Chapter Closer items.
```

Prompt: get recommendations on additional items for zone 2

```
Please evaluate Zone 2: The Main Body. Are there any worked examples you would recommend adding in that section? Are there any formative checks you would recommend adding in that section? It might be nice to have a visual for each main section. What kind of visual would you recommend for each section?
```
