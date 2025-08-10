# Portfolio Projects

This repository showcases my collection of hands-on portfolio projects using **n8n** - a powerful no-code/low-code workflow automation tool. Each project demonstrates real-world integrations, automation techniques, and the visual logic of automation flows.

----------

## Overview

-   **Objective**: To demonstrate practical proficiency in designing, building, and organizing n8n workflows that solve real-world problems.
    
-   **What's inside**:
    
    -   Curated n8n project folders, each containing a complete workflow and relevant documentation.
        
    -   Clear breakdowns of workflow goals, triggers, actions, and integration logic.
        
    -   Ready-to-import JSON files compatible with any n8n instance.
        

----------

## Project Structure

```
	n8n-portfolio/
	│
	├── index.html        		# Main landing page
	├── style.css         		# Styling
	├── projects/
	│   ├── project1/           # individual project directory
	│   │	├── project1.html 	# Individual project page
	│   ├── project2/
	│   │	├── project2.html
	│   └── ...
	├── assets/
	│   ├── images/       		# Screenshots
	│   └── workflows/    		# JSON workflow exports
	└── README.md
	

	Each project folder includes:
	-   `workflow.json`: Exported n8n workflow.
	-   `README.md`: Brief explanation of use case, setup steps, and key nodes.
```    

----------

## Getting Started

1.  **Clone the Repository**
    
```
    git clone https://github.com/WambuaJoe/n8n-Portfolio-Projects.git
    cd n8n-Portfolio-Projects
```
    
2.  **Import a Workflow**
    
    -   Open n8n (locally or in the cloud).
        
    -   Navigate to **Import from File** and select the `.json` file.
        
    -   Review nodes and add any required credentials.
        
    -   Save and **Activate** the workflow.
        

----------

## Featured Workflow Examples

-   **[Workflow Name 1]**: Automates emailing summaries of new CSV data files.
    
-   **[Workflow Name 2]**: Fetches tweets from a specific user and logs them to Google Sheets.
    
-   _(Add your actual workflow examples with a one-liner description)_
    

----------

## Why n8n?

n8n is an open-source workflow automation platform known for:

-   Seamless integrations with services like Telegram, Google Drive, OpenAI, Slack, and more [GitHub](https://github.com/topics/n8n?utm_source=chatgpt.com).
    
-   A visual node-based editor empowering rapid automation without sacrificing customization [GitHub](https://github.com/n8n-io?utm_source=chatgpt.com).
    
-   Flexibility to mix no-code blocks with custom code when needed [GitHub](https://github.com/n8n-io/n8n?utm_source=chatgpt.com).
    

----------

## Contributing

Contributions are welcome! Suggest new workflows, improve existing ones, or add documentation:

1.  Fork the repository
    
2.  Add your workflow in its own folder (`your-workflow-name/`)
    
3.  Include `workflow.json` and a short `README.md`
    
4.  Commit and open a Pull Request
    

----------

## License

This project is released under the **MIT License**. See LICENSE for details.

----------

## Acknowledgements

-   Inspired by the n8n community template collections such as [_awesome-n8n-templates_](https://github.com/enescingoz/awesome-n8n-templates?utm_source=chatgpt.com) and [_n8n-free-templates_](https://github.com/wassupjay/n8n-free-templates?utm_source=chatgpt.com).
    
-   Special thanks to the n8n platform for its robust automation capabilities and community support.
