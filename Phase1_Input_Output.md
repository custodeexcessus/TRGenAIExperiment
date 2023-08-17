# Editorial AI - Phase 1

## Prompt 1

**Note:** This prompt would be most similar to an author writing new sections or subsections. The content needs to fit hierarchically in the existing content, but the context of existing material is not being taken into account.

### **P1-Input**

- New cases
  - Quotes
  - Small summaries of important points
- New legislation
  - A couple sentences of commentary
- New events that impact the law (Think COVID)
  - Explanations of the events and why it impacts the law

### **P1-Output**

- Compilation of quotes and small summaries into an expanded commentary
  - E.g. Might expand 3 quotes and a couple sentences of commentary into 4 paragraphs commenting on the case and why it is relevant.

### **P1-Deliverable**

- The system output might be the commentaries for all inputs, but the deliverable would be all of those commentaries and the author's assessment of where to fit them into the content.

### **P1-Concerns**

- Likely prone to more hallucinations

## Prompt 2

**Note:** This prompt would be most similar to an author writing new paragraphs of material that would need to be inserted contextually into existing material

### **P2-Input**

- New cases
  - Quotes
  - Small summaries of important points
- New legislation
  - A couple sentences of commentary
- New events that impact the law (Think COVID)
  - Explanations of the events and why it impacts the law
- A chapter or section hierarchy with general context
  - This could be the table of contents for a chapter or a detailed outline
  - E.g. The Causes of Action outline.

### **P2-Output**

- Compilation of quotes and small summaries into an expanded commentary
- Insertion of those commentaries into the appropriate places in the outline.

### **P2-Concerns**

- Outline may not provide enough context to properly place material
- Material may not "flow" with existing content

## Prompt 3

**Note:** This prompt would be most similar to an author writing sentences and paragraphs that need to be inserted contextually into existing material

### **P3-Input**

- A chapter or section hierarchy with detailed context
- Think the text of an existing section
- New editorial material inserted into the outline with context before and after

### **P3-Output**

- Expanded editorial material placed appropriately in the hierarchy with appropriate phrasing to maintain "flow" with surrounding context.

### **P3-Concerns**

- Large number of tokens
- Still need to provide context of material before and after
