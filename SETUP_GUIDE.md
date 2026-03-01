# Claude Cowork Setup Guide

## Integration: Awesome Claude Plugins

This repository integrates the **ComposioHQ/awesome-claude-plugins** collection as a Git submodule, giving you access to a curated list of plugins optimized for Claude Cowork.

## What's Included

The awesome-claude-plugins includes:
- Production-ready plugins for Cowork
- Plugin documentation and examples
- Setup instructions for each plugin
- Best practices for Claude Cowork integration

## Getting Started

### 1. Clone the Repository with Submodules

```bash
git clone --recurse-submodules https://github.com/shawnhill21-150/my-cowork-setup.git
cd my-cowork-setup
```

### 2. Initialize Submodules (if already cloned)

If you've already cloned the repo without submodules, run:

```bash
git submodule update --init --recursive
```

### 3. Explore the Plugins

Navigate to the plugins directory:

```bash
cd plugins/awesome-claude-plugins
```

You'll find:
- Individual plugin folders
- README files with plugin descriptions
- Installation instructions for each plugin
- Example configurations

## Adding Plugins to Your Cowork Instance

### Step 1: Select a Plugin
Browse `plugins/awesome-claude-plugins` and choose the plugin(s) you want to use.

### Step 2: Follow Plugin Instructions
Each plugin has its own README with specific setup steps.

### Step 3: Configure for Your Workspace
Adapt the plugin configuration to your Cowork instance settings (API keys, workspace IDs, etc.)

### Step 4: Test and Deploy
Test the plugin in your Cowork instance before deploying to production.

## Keeping Plugins Updated

To update the awesome-claude-plugins submodule to the latest version:

```bash
cd plugins/awesome-claude-plugins
git pull origin main
cd ../..
git add plugins/awesome-claude-plugins
git commit -m "Update awesome-claude-plugins to latest version"
git push
```

## Project Structure

```
my-cowork-setup/
├── .gitmodules
├── SETUP_GUIDE.md
├── README.md
└── plugins/
    └── awesome-claude-plugins/
        ├── README.md
        ├── plugins/
        │   ├── plugin-1/
        │   ├── plugin-2/
        │   └── ...
        └── docs/
```

## Resources

- **Awesome Claude Plugins**: https://github.com/ComposioHQ/awesome-claude-plugins
- **Claude Cowork Docs**: https://claude.com/plugins
- **ComposioHQ**: https://composio.dev

## Support

For issues with:
- **Plugins**: Check the ComposioHQ/awesome-claude-plugins repository
- **Your setup**: Open an issue in this repository
- **Cowork integration**: Consult the official Claude documentation

## Next Steps

1. Review available plugins in `plugins/awesome-claude-plugins`
2. Choose plugins that fit your Cowork workflow
3. Follow each plugin's setup instructions
4. Configure and test in your Cowork instance
5. Deploy to production

Happy coding! 🚀