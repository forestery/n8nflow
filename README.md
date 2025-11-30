# n8nflow - Collection of n8n Workflow Templates

A comprehensive collection of production-ready n8n workflow templates covering everything from simple data processing to complex AI-powered automation systems.

## 🚀 Quick Start

### Importing Workflows

1. Open your n8n instance
2. Click **"Import from file"** in the workflow dashboard
3. Select any `.json` file from this repository
4. Configure your credentials and parameters
5. Activate the workflow

### Requirements

- **n8n**: Version 1.0+ (most workflows work with older versions too)
- **API Credentials**: Most workflows require API keys for integrated services
- **Node.js**: For self-hosted n8n installations

## 📂 Workflow Categories

### 🤖 AI-Powered Workflows

Our most advanced workflows leveraging cutting-edge AI capabilities:

- **[AI Video Generation](./10050-generate-ai-videos-from-text-or-images-with-sora-2pro-and-gpt-5-enhancement.json)** - Create AI videos using Sora 2.0 Pro with GPT-5 enhancement
- **[Lead Qualification System](./10025-automate-interior-design-lead-qualification-with-ai-and-human-approval-to-notion.json)** - Intelligent lead classification with human approval loop
- **[Content Creation Pipeline](./10093-multi-agent-ai-content-creator-for-seo-blogs-and-newsletters-with-openrouter-dall-e-gemini.json)** - Multi-agent system for blog and newsletter creation
- **[Document RAG System](./10096-document-rag-and-chat-agent-google-drive-to-qdrant-with-mistral-ocr.json)** - Chat with your documents using OCR and vector search

### 📈 Marketing & Sales Automation

Comprehensive workflows for marketing campaigns and sales processes:

- **[Email Campaign Automation](./10078-automated-cold-email-campaigns-with-random-templates-and-google-sheets-tracking.json)** - Send personalized cold emails with template rotation
- **[Lead Generation Pipeline](./10045-ai-candidate-screening-pipeline-linkedin-to-telegram-with-gemini-and-apify.json)** - LinkedIn lead screening with AI analysis
- **[Customer Support Triage](./10083-automate-customer-support-triage-with-gpt-gmail-slack-and-analytics-dashboard.json)** - Intelligent customer support routing
- **[Sales Follow-up System](./10052-automated-sales-follow-up-system-using-highlevel-gmail-slack-and-google-sheets.json)** - Automated sales communication tracking

### 📝 Content Creation & Publishing

Automate your content production and distribution:

- **[Blog Post Generator](./10046-generate-blog-posts-from-youtube-videos-with-openai-gpt-for-wordpress-and-webflow.json)** - Convert YouTube videos to blog posts
- **[Podcast Automation](./10051-automate-podcast-creation-with-gpt-claude-and-eleven-labs-text-to-speech.json)** - End-to-end podcast creation pipeline
- **[Social Media Publishing](./10322-twitter-content-automation-with-gemini-ai-for-tweets-images-and-engagement.json)** - Automated Twitter content creation
- **[Video Multi-Platform Publishing](./10358-automate-ai-video-creation-and-multi-platform-publishing-with-gpt-4-veo-31-and-blotato.json)** - Distribute videos across multiple platforms

### 💼 Business Operations & HR

Streamline your business processes:

- **[Employee Onboarding](./10034-automated-developer-onboarding-audit-with-clickup-gpt-4o-mini-and-slack-alerts.json)** - Automated new hire onboarding workflow
- **[Performance Review System](./10005-automate-performance-review-process-with-google-sheets-calendar-email-and-slack.json)** - Streamlined performance management
- **[Payroll Processing](./10007-automate-payroll-processing-with-gpt-4-google-sheets-pdf-payslips-and-slack-alerts.json)** - Automated payroll generation and notification
- **[Invoice Management](./10069-automate-invoice-data-extraction-with-ocrspace-gpt-and-google-sheets.json)** - Extract and process invoice data automatically

### 🔗 Data Management & Integration

Handle data synchronization and processing:

- **[Excel to PostgreSQL](./1-insert-excel-data-to-postgres.json)** - Import Excel data into PostgreSQL database
- **[Multi-Source Data Sync](./10056-shopify-and-woocommerce-inventory-sync-with-google-sheets-alerts.json)** - Synchronize inventory across platforms
- **[Data Transformation Pipeline](./10086-how-to-transform-unstructured-email-data-into-structured-format-with-ai-agent.json)** - Convert unstructured data to structured format
- **[API Integration Testing](./10030-automate-api-faq-quality-testing-with-gpt-4o-mini-google-sheets-and-slack-alerts.json)** - Automated API testing and monitoring

### 📢 Communication & Notifications

Multi-channel communication automation:

- **[Multi-Channel Alerts](./10045-multi-channel-task-reminder-system-with-telegram-email-and-slack.json)** - Send notifications across multiple platforms
- **[Email Auto-Reply System](./10018-gmail-email-categorization-and-auto-reply-with-gpt-4o-and-google-sheets.json)** - Smart email categorization and responses
- **[WhatsApp Business Integration](./10040-handle-whatsapp-customer-inquiries-with-ai-and-intent-routing.json)** - AI-powered WhatsApp customer service
- **[Weather Alert System](./10085-send-severe-weather-alerts-from-visual-crossing-to-telegram.json)** - Automated weather notifications

### 🛒 E-commerce Solutions

Specialized workflows for online retail:

- **[Shopify Order Management](./10037-send-rapiwa-whatsapp-apology-and-reorder-link-when-shopify-order-is-cancelled.json)** - Handle canceled orders with automated outreach
- **[Product Catalog Management](./10063-ai-video-generator-for-ecommerce-product-catalogs-with-veo-31.json)** - Generate product videos using AI
- **[Customer Review Automation](./10027-client-review-collection-and-sentiment-analysis-with-highlevel-gpt-4o-gmail-and-slack.json)** - Collect and analyze customer reviews
- **[Inventory Monitoring](./10015-track-amazon-product-prices-with-scrapegraphai-google-sheets-and-telegram-alerts.json)** - Monitor competitor pricing

## 🌟 Featured Workflows

### 🏠 Interior Design Lead Qualification System
**File:** `10025-automate-interior-design-lead-qualification-with-ai-and-human-approval-to-notion.json`

This sophisticated workflow demonstrates advanced AI integration:

- **AI-Powered Classification**: Uses Google Gemini and OpenAI to classify leads as HOT/WARM/COLD
- **Human-in-the-Loop**: Telegram-based approval system for quality control
- **Multi-Channel Integration**: Forms, Gmail, Notion, and Slack
- **Smart Email Generation**: Personalized outreach based on lead qualification
- **Budget Analysis**: Intelligent evaluation of project scope vs. budget

### 🎥 AI Video Creation Pipeline
**File:** `10050-generate-ai-videos-from-text-or-images-with-sora-2pro-and-gpt-5-enhancement.json`

Cutting-edge video generation workflow:

- **Multi-Model Integration**: Combines OpenAI Sora 2.0 Pro with GPT-5
- **Parallel Processing**: Efficient video generation workflow
- **Content Enhancement**: AI-powered video quality improvement
- **Automated Publishing**: Direct distribution to social platforms

### 📊 Multi-Agent Content Creator
**File:** `10093-multi-agent-ai-content-creator-for-seo-blogs-and-newsletters-with-openrouter-dall-e-gemini.json`

Advanced content creation system:

- **Multi-Agent Architecture**: Specialized AI agents for different content types
- **Image Generation**: DALL-E integration for visual content
- **SEO Optimization**: Built-in search engine optimization
- **Multi-Format Output**: Blogs, newsletters, and social media content

## 🔧 How to Use Workflows

### Step 1: Choose Your Workflow
Browse the categories above and select a workflow that matches your needs.

### Step 2: Import and Configure
1. Import the JSON file into your n8n instance
2. Review the workflow structure and nodes
3. Configure required credentials for each service integration

### Step 3: Customize Parameters
- Adjust input/output formats to match your data
- Modify timing and scheduling preferences
- Set up webhook endpoints for triggers
- Configure error handling and retry logic

### Step 4: Test and Deploy
- Use the test mode to verify functionality
- Monitor execution logs for any issues
- Activate the workflow for production use

## 🔑 Common Credential Requirements

Most workflows require API keys for these services:

- **OpenAI**: For GPT models and DALL-E image generation
- **Google**: Gemini API, Google Drive, Gmail, Sheets
- **Slack**: Workspace access tokens
- **Telegram**: Bot API tokens
- **Notion**: Integration tokens
- **CRM Systems**: HighLevel, HubSpot, Pipedrive credentials
- **E-commerce**: Shopify, WooCommerce API keys

## 🤝 Contributing Guidelines

### Adding New Workflows

1. **Follow Naming Convention**: Use descriptive names with hyphens
   ```
   category-specific-action-with-integrations.json
   ```

2. **Include Documentation**: Add sticky notes explaining complex logic

3. **Test Thoroughly**: Ensure all nodes are properly configured

4. **Provide Example Data**: Include sample data for testing

5. **Update Categories**: Add your workflow to the appropriate section in this README

### Workflow Structure Best Practices

- Use clear node names that describe their function
- Include error handling where appropriate
- Add sticky notes for complex business logic
- Use environment variables for sensitive data
- Provide setup instructions in node descriptions

## 📋 Requirements by Category

### AI Workflows
- OpenAI API key (GPT-4, DALL-E, Sora)
- Google API access (Gemini, Drive, etc.)
- Sufficient API quota for production use

### Marketing Automation
- Email service credentials (Gmail, SendGrid, etc.)
- CRM system access (HubSpot, Salesforce, etc.)
- Social media API keys

### Data Integration
- Database credentials (PostgreSQL, MySQL, etc.)
- Cloud storage access (Google Drive, AWS S3, etc.)
- API tokens for source/target systems

### E-commerce
- Shopify/ WooCommerce API keys
- Payment gateway credentials
- Inventory management system access

## 🎯 Use Case Examples

### Small Business Automation
Combine multiple workflows to create a complete business automation system:
1. **Lead Capture** → Form to CRM integration
2. **Lead Qualification** → AI-powered scoring
3. **Customer Communication** → Automated email sequences
4. **Order Processing** → E-commerce automation
5. **Support** → Multi-channel customer service

### Content Marketing Pipeline
Automate your entire content marketing workflow:
1. **Content Ideas** → AI-powered topic generation
2. **Content Creation** → Automated writing and image generation
3. **Review Process** → Human approval workflow
4. **Publishing** → Multi-platform distribution
5. **Analytics** → Performance tracking and reporting

### Data Operations
Build robust data management systems:
1. **Data Collection** → Multi-source data ingestion
2. **Processing** → Transformation and enrichment
3. **Quality Control** → Automated validation and cleaning
4. **Storage** → Database and file system integration
5. **Monitoring** → Error tracking and alerting

## 📚 Additional Resources

- [n8n Official Documentation](https://docs.n8n.io/)
- [n8n Community Forum](https://community.n8n.io/)
- [API Integration Guides](https://docs.n8n.io/integrations/)
- [Workflow Best Practices](https://docs.n8n.io/workflows/best-practices/)

## 📄 License

This collection of workflows is provided as-is for educational and commercial use. Please ensure compliance with the terms of service of all integrated platforms and APIs.

## 🆘 Support

For workflow-specific questions:
1. Check the sticky notes within each workflow for documentation
2. Review the n8n documentation for node-specific guidance
3. Visit the n8n community forums for general questions
4. Test workflows in a development environment before production use

---

**Happy Automating! 🚀**

Transform your business processes with these powerful n8n workflow templates. Whether you're just starting with automation or building complex AI-powered systems, you'll find workflows that accelerate your development and boost productivity.
