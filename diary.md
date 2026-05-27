## Week 8: Initial CSV Processing
### AI Collaboration #1
**Context**: Setting up basic CSV loading and analysis for transaction data.
**Artifact**: A written record of the design prompt given to the AI assistant.
**Prompt**: "Help me load and analyze transaction CSV data for my finance assistant".
**Result**: Working pandas code with data cleaning and summary statistics.
**Reflection**: AI provided good starting code, but I had to ask for better error handling to deal with edge cases.

### AI Collaboration #2
**Context**: Creating spending summary by category.
**Artifact**: A text log record of the data manipulation prompt.
**Prompt**: "Calculate total spending by category and format for business presentation".
**Result**: Professional-looking output with proper formatting.
**Reflection**: Learned to be specific about output formatting requirements to match a clean user interface.

## Week 8: Stock API Integration & Data Visualization
### AI Collaboration #1
**Context**: Selecting a beginner-friendly stock API and setting up the live connection requests.
**Artifact**: A text record of a prompt provided to the AI assistant to explore free data endpoints.
**Prompt**: "Whatvare some free stock APIs I can use for learning? I want to get basic stock price data."
**Result**: Structured a function 'get_stock-data()' utilizing the Python 'requests' library to connect to Alpha Vantage's JSON data endpoint ('TIME_SERIES_DAILY').
**Reflection**: The AI correctly helped map out parameter dictionaries ('function', 'symbol', 'apikey'). However, I learned that Alpha Vantage places strict  limits on the free tier (5 calls per minute), which means i have to manage testing cell runs carefully to avoid hitting rate limits.

## AI Collaboration #2
**Context**: Parsing the nested API JSON response structure into an organized tabular DataFrame.
**Artifact**: A text log record of data cleaning and structure alignment prompts.
**Prompt**: "Convert API response to pandas DataFrame. Clean up column names to Open, High, Low, Close, Volume, and convert index to datetime."
**Result**: Working code extracting data from the nested "Time Series (Daily)" string object dictionary, organizing index datatypes, and mapping column headers cleanly.
**Reflection**: Nesting dictionary payloads can be highly confusing to handle manually. AI successfully demonstrated how to use 'pd.DataFrame.from_dict(time_series, orient='index')', which taught me how to easily realign API response data shapes on an index axis.
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

## Entry 4 - Gradio UI
**Artifact**: A written record of AI assistance used to build the Gradio web interface.
**Context**: I needed to connect my CSV analysis and savings calculator into one simple use interface.
**Reflection**: AI helped structure the Gradio tabs, file upload, output boxes, and calculator inputs. I faced issues with hidden button and layout, but after testing, the interface worked successfully.I learned how Gradio connects frontend inputs with Python backend functions.

## Entry 5 - Testing
**Artifact**: A written record of AI assistance used to create test datasets and testing functions.
**Context**: I needed to prove that the finance assistant works with normal data, invalid data, refunds, missing values, and empty datasets.
**Reflection**: AI helped create test cases using assert statements. The tests confirmed that the cleaning, analysis, and recommendation functions worked correctly.

## Entry 6 - Final Integration
**Artifact**: A written record of AI assistance used to connect the full workflow and prepare the final project.
**Context**: I needed to complete the notebook, run the app, commit changes to Github, and prepare documentation.
**Reflection**: AI helped me debug Github, Colab, Gradio, and package installation issues. I learned how to commit updates, write project documentation, and finalise a working application. This project improved my confidence in using AI as a coding assistant while still reviewing and improving the solution myself.

## Final Reflection 
This project helped me learn Python data analysis, Gradio interface development, testing , debugging, and Github version control. AI was useful throughout the project, but i still needed to check outputs, fix errors, and make decisions. I learned that AI is most effective when I provide clear prompts, review the code carefully, and test the final result.


