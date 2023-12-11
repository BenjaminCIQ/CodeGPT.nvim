# Description
Create a GPT-powered plain text interpreter for vim commands. 
Should be well integrated into the existing command line workflow, and enact the interpreted instructions directly on the file. An explanation of the generated command should be shown in a visible yet unobtrusive manner.

# Features
1. GPT code interpreter added to command line
2. Resulting command directly enacted on text
3. Subtle display and explanation of the command
4. Very visible token count for session and overall, compared to current funds
4. Saved and searchable history of commands used

# Development Steps
1. Design perfect prompt to get the desired command from GPT [x] 
2. Test current plugin
2. Rename current prompt to shorter input
3. Set the instruction to default to interpreter
4. Define required arguments necessary for more seamless prompts (eg, passing current line number)

