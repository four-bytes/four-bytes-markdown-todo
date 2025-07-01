# Four Markdown Todo

Open source Vue.js markdown todo list manager with GitHub and Nextcloud compatibility.

## Features

- **Multi-file todo management** - Organize todos across multiple markdown files
- **Universal compatibility** - Works with GitHub, Nextcloud, and local files
- **Standard markdown format** - Uses GitHub-style checkboxes (`- [ ]` and `- [x]`)
- **Real-time sync** - Synchronize across different platforms
- **Offline-first** - Works without internet connection

## Architecture

### Frontend (Vue.js 3)
- Modern Vue 3 with Composition API
- Responsive design for desktop and mobile
- Real-time markdown preview
- Drag-and-drop file support
- Offline-first with local storage

### Backend (Lightweight API)
- RESTful API for todo management
- Multiple storage backends:
  - Local filesystem
  - GitHub repositories
  - WebDAV (Nextcloud/ownCloud)
- File format validation and conversion

## TODO.md Format

This application supports the standardized TODO.md format:

```markdown
# Work Tasks
- [ ] Complete project proposal
- [x] Review team documentation
- [ ] Schedule client meeting

# Personal Tasks  
- [ ] Book vacation
- [x] Pay bills
- [ ] Call mom
```

## Supported Integrations

- ✅ **GitHub** - Manage todos in repository files
- ✅ **Nextcloud** - Sync via WebDAV protocol
- ✅ **ownCloud** - WebDAV compatibility
- ✅ **Local Files** - Direct file system access
- ✅ **Standard Markdown** - Compatible with any markdown editor

## Installation

### Prerequisites
- Node.js 18+
- PHP 8.2+ (for backend)
- Git

### Development Setup

1. Clone the repository:
```bash
git clone https://github.com/four-bytes/four-markdown-todo.git
cd four-markdown-todo
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
npm run dev
```

3. Install backend dependencies:
```bash
cd backend
composer install
php bin/console server:run
```

## Usage

1. **Create todo files** in standard markdown format
2. **Connect integrations** (GitHub, Nextcloud, local files)
3. **Manage todos** through the web interface
4. **Sync automatically** across all connected platforms

## Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

### Development Guidelines
- Follow Vue.js 3 best practices
- Use TypeScript for type safety
- Write tests for new features
- Follow semantic versioning
- Update documentation

## License

MIT License - see [LICENSE](LICENSE) for details.

## Support

- 🐛 **Issues:** [GitHub Issues](https://github.com/four-bytes/four-markdown-todo/issues) for bug reports and feature requests
- 💬 **Discussions:** [GitHub Discussions](https://github.com/four-bytes/four-markdown-todo/discussions) for community support and questions
- 📖 **Documentation:** Check the wiki and README for detailed information