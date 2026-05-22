## Week 8: Initial CSV Processing

### AI Collaboration #1
**Context**: Setting up basic CSV loading and analysis for transaction data
**Prompt**: "Help me load and analyze transaction CSV data for my finance assistant"
**Result**: Working pandas code with data cleaning and summary statistics
**Reflection**: AI provided good starting code, but I had to ask for better error handling

### AI Collaboration #2
**Context**: Creating spending summary by category
**Prompt**: "Calculate total spending by category and format for business presentation"
**Result**: Professional-looking output with proper formatting
**Reflection**: Learned to be specific about output formatting requirements
## Additional Project Reflection
# Developer's Diary - Smart Finance Assistant
## Entry 1 - CSV Data Processing
**Artifact**: A written record of AI assistance used to create and improve the CSV loading and cleaning function.
**Context**: I needed to load transaction data, clean missing values, convert amounts into numeric format, and prepare the data for financial analysis.
**Reflection**: AI helped generate the first version of the data cleaning function. I reviewed the code and improved it by handling missing dates, invalid amounts, refunds, duplicate rows, and missing categories. This taught me that AI-generated code needs testing and adjustments before it can be used in a real project.

## Entry 2 - Spending Analysis
**Artifact**: A written record of AI assistance used to create spending summaries and category-based financial analysis.
**Context**: I wanted the assistant to calculate total spending, refunds, not spending, and category summaries from transaction data.
**Reflection**: AI helped me design the analysis logic using Pandas. I learned how to group spending by category and calculate meaningful financial summaries. I also improved the output so it looked more useful for a personal finance user.

## Entry 3 - Savings Goal Calculator
**Artifact**: A written record of AI assistance used to create a custom savings calculator tool.
**Context**: I needed one custom financial tool for the project. I created a calculator that uses current savings, monthly contribution, and target amount to estimate the time needed to reach a goal.
**Reflection**: AI helped create the basic function , but i had to fix errors and test it inside Gradio. I learned the improtance of input validation, especially when monthly contribution is zero or the target has already been reached.
# Entry 4 - Gradio UI
**Artifact**: A written record of AI assistance used to build the Gradio web interface.
**Context**: I needed to connect my CSV analysis and savings calculator into one simple use interface.
**Reflection**: AI helped structure the Gradio tabs, file upload, output boxes, and calculator inputs. I faced issues with hidden button and layout, but after testing, the interface worked successfully.I learned how Gradio connects frontend inputs with Python backend functions.


