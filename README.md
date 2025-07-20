# Model-Development-Protocol
An open ended, theory based method for fine tuning models in simplified interfaces based on pre-prompts and document processing. e.g. via OpenAI GPT builder 



## 1. Knowledge Base Preparation and Management

### 1.1 Document Formatting Standards
- **Preferred Formats**: Text-searchable PDFs, `.txt`, or `.md` (Markdown).
- **Cleaning**: Remove irrelevant headers, footers, page numbers, sidebars, ads, navigation links, and legal disclaimers not relevant to content.
- **Text Clarity**: Ensure all important information is in plain text; avoid reliance on color or layout for meaning.
- **Structure**:
  - Use clear headings (e.g., Heading 1/2).
  - Leverage bullet lists, tables, and logical paragraphs.
- **Chunking**:
  - Large documents should be split into smaller, topic-focused files for more efficient retrieval and context.
 
- Larger documents benefit from intial summaries of content within aiding in future document based retrivals

### 1.2 File Naming Convention
- **Standard Format**: `[Department]_[Topic]_[YYYY-MM-DD]_[Version].pdf`
- **Example**: `HR_Parental-Leave-Policy_2025-07-15_v2.1.pdf`
- **Purpose**: Enables easy source identification, streamlined version control, and accurate citation.

### 1.3 Content Principles
- **Factuality**: State facts clearly and unambiguously.
- **Self-Contained Documents**: Each file covers its topic completely to minimize the need for multi-file reference.

