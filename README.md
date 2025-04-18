# Bug Bounty Search Engine

A powerful and intuitive web-based search engine designed specifically for bug bounty hunters and security researchers. This tool provides quick access to various Google dorks and specialized searches to help identify potential security vulnerabilities and gather information about target domains.

![Screenshot](screenshot.png)

## Features

- **Comprehensive Search Categories**:
  - File & Directory Discovery
  - Web Application Discovery
  - Information Gathering
  - Cloud & Infrastructure
  - API & Development
  - Archives & Historical

- **User-Friendly Interface**:
  - Modern, responsive design
  - Intuitive category-based organization
  - Visual feedback for clicked searches
  - Dark theme optimized for extended use

- **Advanced Features**:
  - Google Custom Search API integration
  - Search history tracking
  - Direct links to specialized security tools
  - Customizable API configuration

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/bug-bounty-search-engine.git
   cd bug-bounty-search-engine
   ```

2. **Google Custom Search API Setup** (Optional):
   - Create a project in the [Google Cloud Console](https://console.cloud.google.com/)
   - Enable the Custom Search API
   - Create API credentials
   - Create a Custom Search Engine at [Google Programmable Search](https://programmablesearchengine.google.com/)
   - Configure the API key and Search Engine ID in the tool

## Usage

1. Open `dorking.html` in your web browser
2. Enter your target domain in the search field
3. Click on any of the categorized search buttons to perform specialized searches
4. Results will open in a new tab
5. Use the "Reset Tracking" button to clear your search history

## API Configuration

To use the Google Custom Search API:

1. Click the "CSE API Key" button in the top-right corner
2. Enter your API Key and Search Engine ID
3. Click "Test Connection" to verify the setup
4. Save the configuration

## Categories Overview

### File & Directory Discovery
- Directory listing vulnerabilities
- Exposed configuration files
- Database files
- Log files
- Backup files
- And more...

### Web Application Discovery
- Login pages
- SQL errors
- phpinfo() pages
- WordPress installations
- Backdoors
- And more...

### Information Gathering
- Pastebin entries
- LinkedIn employees
- Sensitive files
- Subdomains
- SSL certificates
- And more...

### Cloud & Infrastructure
- AWS S3 buckets
- Jenkins instances
- Kubernetes dashboards
- Docker API
- Firebase instances
- And more...

### API & Development
- GitHub dorks
- GraphQL endpoints
- API documentation
- Environment files
- And more...

### Archives & Historical
- Archive.org searches
- Historical domain data
- Crossdomain.xml
- And more...

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- **Boopathi S**
  - LinkedIn: [Boopathi S](https://www.linkedin.com/in/boopathi-s/)

## Acknowledgments

- Inspired by various bug bounty methodologies and tools
- Built with HTML, CSS, and JavaScript
- Uses Google Custom Search API for enhanced search capabilities

## Disclaimer

This tool is intended for legitimate security research and bug bounty hunting purposes only. Always ensure you have proper authorization before testing any systems. The author is not responsible for any misuse of this tool. 