# Coding-with-Claude-AI
Experience new tools
Prereq:
1. Install Node.js
2. Create a directory for global installations
mkdir ~/.npm-global

# Configure npm to use the new directory path
npm config set prefix '~/.npm-global'

# Add the new directory to your PATH
echo 'export PATH=~/.npm-global/bin:$PATH' >> ~/.zshrc
source ~/.zshrc

# Now install claude-code
npm install -g @anthropic-ai/claude-code
