# n8n Webhook Tester Pro

A comprehensive, professional-grade webhook testing interface specifically designed for **n8n workflows** with advanced features, rate limiting, and intelligent response analysis.


## 🚀 Features

### Core Testing Capabilities
- **Multi-Method Support**: GET, POST, PUT, DELETE, PATCH requests
- **Authentication**: Bearer tokens, Basic auth, API keys, custom headers
- **Real-time Response Analysis**: JSON formatting, HTML preview, performance metrics
- **Smart Rate Limiting**: 50 requests/minute protection against abuse

### Advanced Interface
- **Professional Design**: Modern blue theme with clean typography
- **Adjustable Layout**: Drag-to-resize sidebar (300px - 600px width)
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Dark/Light Optimized**: Professional color scheme for extended use

### Response Analysis
- **Intelligent Formatting**: Auto-detection of JSON, HTML, and plain text
- **AI-Enhanced Preview**: Special preview mode for complex JSON responses
- **Performance Monitoring**: Response times, success rates, payload sizes
- **Export Capabilities**: Postman collections, response data, performance reports

### Testing Automation
- **Test Scenarios**: Happy path, error cases, edge cases, performance testing
- **JSON Schema Validation**: Schema generation, sample data creation, validation
- **Load Testing**: Concurrent requests with configurable delays and limits
- **Request History**: 50-request history with one-click replay

### Developer Experience
- **Environment Management**: Dev/staging/production URL presets
- **Collection Management**: Save, load, and export request collections
- **Chat Interface Testing**: Built-in n8n chat webhook testing
- **URL Builder**: Intuitive base URL + path construction

## 🛠️ Installation

### Direct Download
1. Download the `n8n-webhook-tester.html` file
2. Open in any modern web browser
3. Start testing immediately - no server required!


## 📖 Usage

### Quick Start
1. **Enter Webhook URL**: Your n8n webhook endpoint
2. **Configure Request**: Select HTTP method, add headers, authentication
3. **Set Request Body**: Use presets or write custom JSON
4. **Send Request**: Click "Send Webhook" and analyze response
5. **Review Results**: Check formatted response, headers, and performance

### Advanced Features

#### Environment Management
```javascript
// Set up multiple environments
Dev: https://dev-n8n.example.com
Staging: https://staging-n8n.example.com  
Production: https://n8n.example.com
```

#### JSON Schema Validation
```json
{
  "type": "object",
  "properties": {
    "name": {"type": "string"},
    "email": {"type": "string", "format": "email"}
  },
  "required": ["name", "email"]
}
```

#### Load Testing
- **Requests**: 1-100 (rate limited to 50/minute)
- **Delay**: 100ms - 10s between requests
- **Concurrency**: 1-10 simultaneous requests

## 🔧 Technical Details

### Architecture
- **Single Page Application**: Pure HTML/CSS/JavaScript
- **No Dependencies**: Except for optional n8n chat module
- **Local Storage**: Environments, collections, and history
- **Rate Limiting**: Client-side request tracking with 60-second windows

### Browser Compatibility
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

### Security Features
- **Rate Limiting**: Prevents abuse with 50 requests/minute limit
- **Input Validation**: JSON schema validation and sanitization
- **No Data Persistence**: All data stored locally in browser
- **CORS Handling**: Proper cross-origin request management

## 🎯 Use Cases

### n8n Workflow Development
- Test webhook triggers before deployment
- Validate data transformation accuracy
- Debug workflow execution issues
- Performance testing for production readiness

### API Development & Testing
- Rapid prototyping and validation
- Schema-driven development
- Load testing and performance analysis
- Documentation and collection sharing

### QA & Testing Teams
- Automated test scenario execution
- Regression testing for webhook endpoints
- Performance benchmarking
- Error condition validation

## 📊 Performance Monitoring

The tool provides comprehensive metrics:
- **Response Time**: Average, min, max across all requests
- **Success Rate**: Percentage of successful responses
- **Request Volume**: Total requests sent in session
- **Payload Analysis**: Response size and content type tracking

## 🔄 Rate Limiting Details

To prevent abuse and protect target servers:
- **Limit**: 50 requests per 60-second window
- **Tracking**: Client-side with automatic cleanup
- **Load Testing**: Additional restrictions on concurrent requests
- **User Feedback**: Clear warnings when approaching limits


### Development Setup
1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes
4. Test thoroughly across browsers
5. Submit a pull request

### Reporting Issues
- Use the GitHub Issues tab
- Include browser version and steps to reproduce
- Provide example webhook URLs (if public)
- Screenshots help!

## 📝 Changelog

### Version 1.0.0 (2024)
- ✨ Initial release with full feature set
- 🎨 Professional blue theme design
- 🔧 Adjustable sidebar interface
- 🛡️ Rate limiting implementation
- 📊 Advanced response analysis
- 🧪 Automated test scenarios
- 💾 Collection management system

## 📄 License

This project is licensed under the MIT License - see the https://opensource.org/license/mit for details.

## 🙏 Acknowledgments

- **n8n Team**: For creating an amazing automation platform
- **Claude AI**: For collaborative development assistance
- **Open Source Community**: For inspiration and best practices
- **Contributors**: Everyone who helps improve this tool

## 🌟 Star History

If this tool helps you with n8n development, please consider giving it a star! ⭐

## 📬 Contact

- **Issues**: Use GitHub Issues for bug reports and feature requests
- **Discussions**: Use GitHub Discussions for questions and ideas
- **LinkedIn**: [Connect with the creator](https://www.linkedin.com/in/idsinghbhambra/)

---

**Built with ❤️ for the n8n community**
