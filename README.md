## Nice DevOps Stack Tools & VS Code Extensions 🚀

This repository contains a curated collection of useful DevOps tools and VSCode extensions to streamline your development and operations workflows. Whether you’re working with Infrastructure-as-Code (IaC), container orchestration, cloud management, or Kubernetes, these tools and extensions aim to enhance your productivity, security, and efficiency.

Whether you're automating deployments, managing Kubernetes, or just improving your VS Code experience, this README highlights tools to help you work smarter, not harder.

### Tools 🛠
#### Cloud
<details>
  <summary><a href=https://github.com/Noovolari/leapp>Leapp</a></summary>
  
  Leapp is an open-source, cross-platform desktop application designed to streamline and secure access to multiple cloud accounts. It offers a unified workflow for managing cloud credentials, automating daily operations, and enhancing security through short-lived credentials.
  - Features:
    - Leapp supports various Identity and Access Management (IAM) methods, including AWS SSO, Okta(coming soon), OneLogin(coming soon), and AzureAD, allowing seamless access to multiple cloud accounts.
    - The application automates routine cloud operations, such as provisioning sessions and accessing web consoles, saving time and reducing manual errors.
    - Leapp generates short-lived credentials, adhering to the Zero-Trust security model, which minimizes the risk of unauthorized access.
    - Leapp offers browser extensions for Firefox and Chrome, enabling users to open multiple AWS consoles from different accounts directly within the browser.
</details>

<details>
  <summary><a href=https://github.com/localstack/localstack>LocalStack</a></summary>
  
  LocalStack is a fully functional local AWS cloud stack that enables developers to run AWS services on their local machines. It simulates a large subset of AWS services for testing and development, providing a way to develop and test cloud applications without the need for an actual AWS account or network connection.
  - Features:
    - Is ideal for developers who need to test AWS-based applications locally. It allows for rapid testing without incurring AWS costs or relying on a network connection to AWS.
    - Mimics the behavior of real AWS services, which allows you to use AWS SDKs, AWS CLI, and other AWS tools directly with the local environment.
    - Runs in Docker containers, making it easy to deploy and integrate into local development environments.
    - Is highly customizable, allowing developers to extend or modify the service simulation according to their needs.
    - It's commonly used in continuous integration and deployment (CI/CD) pipelines for local testing and development, reducing the dependency on remote cloud resources.
</details>

#### IaC
<details>
  <summary><a href=https://github.com/ansible/ansible-lint>Ansible Lint</a></summary>
  
  Ansible-Lint is a command-line tool that checks Ansible playbooks, roles, and tasks for best practices and common errors. It ensures consistency and quality in your Ansible code by applying rules and guidelines to detect issues before execution.
  - Features:
    - Validates your playbooks against Ansible’s recommended coding standards.
    - Encourages writing cleaner, more maintainable playbooks.
    - Identifies common issues like deprecated modules, invalid syntax, or misconfigurations.
    - Supports custom linting rules to match your team’s specific guidelines or requirements.
    - Easily integrates into continuous integration pipelines to ensure quality in automated workflows.
    - Provides clear descriptions and suggestions for fixing detected issues.
</details>

<details>
  <summary><a href=https://github.com/terraform-docs/terraform-docs>Terraform Docs</a></summary>
  
  Terraform Docs is a tool for generating documentation for Terraform modules. It automatically generates a markdown file with a module’s input, output, and other configuration details, ensuring consistent and up-to-date documentation.
  - Features:
    - Generates Terraform module documentation in Markdown format.
    - Automatically includes module inputs, outputs, and metadata.
    - Helps maintain accurate documentation for Terraform modules.
    - Supports customization of the output format and content.
</details>

<details>
  <summary><a href=https://github.com/terraform-linters/tflint>Terraform Lint</a></summary> 

  Terraform Lint is a static analysis tool for Terraform code that checks for syntax and best practices issues. It helps you follow Terraform best practices, reduce errors, and ensure high-quality infrastructure code.
  - Features:
    - Analyzes Terraform code for errors, warnings, and best practices.
    - Supports configuration of custom rules and checks.
    - Can be integrated into CI/CD pipelines for automated linting.
    - Helps ensure that Terraform code is clean and maintainable.
</details>

<details>
  <summary><a href=https://github.com/im2nguyen/rover>Rover</a></summary> 

  Rover is a lightweight tool that transforms Terraform plans into an interactive, visual decision tree. It simplifies plan reviews, making it easier to analyze changes and understand resource dependencies.
  - Features:
    - Displays Terraform plan changes in a tree structure.
    - Works with terraform show -json outputs.
    - Explore resource details and attribute changes.
    - Ideal for team reviews and presentations.
</details>

####

#### Containers
<details>
  <summary><a href=https://github.com/hadolint/hadolint>Hadolint</a></summary>

  Hadolint is a linter for Dockerfiles that checks for best practices, security vulnerabilities, and syntax issues. It helps maintain consistent, error-free Dockerfile configurations by providing linting feedback, encouraging cleaner, more secure Docker images.
  - Features:
    - Validates Dockerfiles against best practices and security guidelines.
    - Provides suggestions for optimizing Docker images and improving performance.
    - Detects security risks such as using outdated base images or insecure commands.
    - You can configure the linter to enable or disable specific rules based on your needs.
    - Easily integrates into continuous integration pipelines for automated Dockerfile linting.
</details>

<details>
  <summary><a href=https://helm.sh/docs/intro/quickstart>Helm</a></summary>

  Helm is a package manager for Kubernetes that helps you define, install, and upgrade even the most complex Kubernetes applications. Helm uses "charts" to describe Kubernetes resources, making it easier to deploy applications.
  - Features:
    - Manages Kubernetes applications with Helm charts.
    - Simplifies application deployment and management with reusable templates.
    - Supports versioning and upgrading of Kubernetes apps.
    - Can manage Kubernetes resources like deployments, services, and more.
</details>

<details>
  <summary><a href=https://github.com/helmfile/helmfile>HelmFile</a></summary>

  Helmfile is a declarative configuration tool for managing multiple Helm charts in Kubernetes environments. It allows you to define and manage a set of charts in a single file, simplifying complex Helm deployments.
  - Features:
    - Manage multiple Helm charts across environments.
    - Provides a way to keep Helm releases consistent.
    - Supports values and secrets management.
    - Integrates with GitOps workflows for consistent deployments.
</details>

<details>
  <summary><a href=https://kubernetes.io/docs/tasks/tools/install-kubectl-linux>Kubectl</a></summary>

  kubectl is the command-line tool for interacting with Kubernetes clusters. It allows you to manage Kubernetes resources, view cluster status, and deploy applications directly from the command line.
  - Features:
    - Deploy, inspect, and manage applications in Kubernetes clusters. 
    - Create, update, and delete Kubernetes resources (pods, services, deployments, etc.).
    - Scale applications, manage namespaces, and debug issues.
    - Supports port forwarding, log streaming, and exec into containers.
</details>

<details>
  <summary><a href=https://github.com/pulumi/kubespy>KubeSpy</a></summary>

  Kubespy is a tool for inspecting Kubernetes resources in real-time. It allows you to view the live status of Kubernetes resources and their relationships, which is useful for debugging and monitoring applications.
  - Features:
    - Real-time inspection of Kubernetes resources (pods, deployments, etc.).
    - Displays a live view of the state and status of resources.
    - Provides a graphical interface for exploring resource relationships.
    - Helps monitor and debug Kubernetes clusters interactively.
</details>

<details>
  <summary><a href=https://github.com/jonmosco/kube-ps1>Kube-PS1</a></summary>

  kube-ps1 is a shell prompt tool that shows the current Kubernetes context and namespace in your terminal prompt. This makes it easier to track and manage multiple Kubernetes clusters from the command line.
  - Features:
    - Displays Kubernetes context and namespace in the terminal prompt.
    - Helps prevent accidental interactions with the wrong cluster.
    - Supports customization of the prompt format and appearance.
    - Ideal for multi-cluster environments to provide clear visibility.
</details>

<details>
  <summary><a href=https://github.com/stern/stern>Stern</a></summary>

  Stern is a multi-pod and multi-container log tailing tool for Kubernetes. It helps you aggregate and stream logs from multiple containers and pods in real-time, making debugging and monitoring easier.
  - Features:
    - Tail logs from multiple Kubernetes pods and containers.
    - Supports filtering by pod name, container name, or label.
    - Provides real-time log aggregation.
    - Useful for debugging and monitoring Kubernetes applications.
</details>

<details>
  <summary><a href=https://github.com/solo-io/squash>Squash</a></summary>

  Squash is a debugger for Kubernetes applications. It provides an interactive debugging experience by connecting to running containers, allowing you to troubleshoot application issues in real-time.
  - Features:
    - Interactive debugger for containers running in Kubernetes.
    - Supports multiple languages (Java, Node.js, Python, etc.).
    - Integrates with existing Kubernetes setups and tools.
    - Allows for real-time breakpoints, variable inspection, and debugging sessions.
</details>

####

#### Security
<details>
  <summary><a href=https://github.com/bridgecrewio/checkov>Checkov</a></summary>

  Checkov is a static analysis tool for scanning Terraform, CloudFormation, Kubernetes, and other infrastructure-as-code (IaC) files to detect security and compliance issues.
  - Features:
    - Scans IaC files for misconfigurations and security vulnerabilities.
    - Works with Terraform, Kubernetes, and CloudFormation.
    - Provides detailed reports on identified issues and recommendations for fixes.
    - Can be integrated into CI/CD pipelines for automated checks.
</details>

<details>
  <summary><a href=https://github.com/aquasecurity/kube-bench>Kube Bench</a></summary>
  
  kube-bench is an open-source tool that checks whether Kubernetes clusters are configured according to security best practices as defined by the CIS Kubernetes Benchmark. It helps identify potential security vulnerabilities and misconfigurations in Kubernetes environments.
  - Features:
    - Covers checks for Kubernetes components such as: API Server, Controller Manager, Scheduler, Kubelet, Etcd.
    - Supports multiple Kubernetes versions, ensuring the benchmarks are relevant to your specific cluster version.
    - You can add or skip specific checks based on your security policies or cluster requirements.
    - Generates detailed reports highlighting failed, passed, and skipped tests, making it easy to prioritize remediation.
    - Works with clusters running on managed services like EKS, AKS, and GKE, as well as self-managed Kubernetes environments.
    - Can run directly on a Kubernetes node, as a Kubernetes Job, or even as a containerized tool.
</details>

<details>
  <summary><a href=https://github.com/aquasecurity/tfsec>TF Sec</a></summary>
  
  TF Sec is a static analysis security scanner for Terraform code. It scans your Terraform files for security vulnerabilities and compliance issues, providing detailed feedback and remediation suggestions.
  - Features:
    - Scans Terraform code for security vulnerabilities and misconfigurations.
    - Provides a report with severity levels and actionable remediation.
    - Helps ensure Terraform infrastructure is secure by default.
    - Integrates with CI/CD pipelines for automated security checks.
</details>

### VSCode Extensions 💻
<details>
  <summary><a href=https://marketplace.visualstudio.com/items?itemName=redhat.ansible>Ansible</a></summary>

  The Docker extension for VS Code makes it easy to work with Docker containers and images directly from the editor. It simplifies the development, building, and management of Dockerized applications.
  - Features:
    - Manage Docker containers, images, and volumes from VS Code.
    - Build, run, and debug Docker containers and apps.
    - Dockerfile and docker-compose file syntax highlighting.
    - Intellisense for Docker commands and configurations.
    - Integration with Azure and other cloud platforms for container deployment.
</details>

<details>
  <summary><a href=https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker>Docker</a></summary>

  The Docker extension for VS Code makes it easy to work with Docker containers and images directly from the editor. It simplifies the development, building, and management of Dockerized applications.
  - Features:
    - Manage Docker containers, images, and volumes from VS Code.
    - Build, run, and debug Docker containers and apps.
    - Dockerfile and docker-compose file syntax highlighting.
    - Intellisense for Docker commands and configurations.
    - Integration with Azure and other cloud platforms for container deployment.
</details>

<details>
  <summary><a href=https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio>Draw.io</a></summary>

  The Draw.io Integration extension brings the popular diagramming tool, Draw.io, directly into VS Code. It allows users to create, edit, and save diagrams without leaving their coding environment.
  - Features:
    - Create flowcharts, UML diagrams, architecture diagrams, and more directly in VS Code.
    - Supports .drawio, .svg, .png, and .xml formats for saving and exporting diagrams.
    - Works natively within VS Code without needing to open a browser.
    - Diagrams can be version-controlled as they are saved as files within your project.
</details>

<details>
  <summary><a href=https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap>CodeSnap</a></summary>

  The CodeSnap extension allows you to take beautiful screenshots of your code, which is especially useful for sharing code snippets on social media, blogs, or presentations.
  - Features:
    - Capture code in a stylish format with customizable themes.
    - Easy one-click screenshot capture from the editor.
    - Resize and adjust the code snapshot before saving it.
</details>

<details>
  <summary><a href=https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens>Error Lens</a></summary>
  
  The Error Lens extension improves the visibility of errors and warnings in your code, making them more prominent so you can quickly address issues.
  - Features:
    - Highlights errors and warnings directly in the code with a colored underline.
    - Displays error messages inline, next to the code.
    - Works with various programming languages (JavaScript, Python, TypeScript, etc.).
    - Customizable error and warning message formatting.
    - Improves code readability by placing attention on issues as you type.
</details>

<details>
  <summary><a href=https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens>GitLens</a></summary>
  
  GitLens is an advanced Git extension for VS Code that enhances the built-in Git capabilities, providing rich insights and visualization to better understand your code’s history and evolution.
  - Features:
    - Line and file-level blame annotations.
    - Commit and history exploration with rich commit details.
    - Git status and history graphs for file changes.
    - Search for commits, branches, and repositories.
    - Integrates with GitHub, GitLab, and other Git platforms for enhanced workflows.
</details>

<details>
  <summary><a href=https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools>Kubernetes</a></summary>
  
  The Kubernetes extension integrates Kubernetes features directly into Visual Studio Code, providing a user-friendly interface for managing clusters and resources.
  - Features:
    - Manage clusters and namespaces from within VS Code.
    - Browse and interact with Kubernetes resources (pods, deployments, etc.).
    - Support for Helm charts and kubeconfig management.
    - YAML validation and autocompletion for Kubernetes manifests.
    - Ability to run kubectl commands from VS Code.
</details>

<details>
  <summary><a href=https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one>Markdown All in One</a></summary>
  
   The Markdown All in One extension provides enhanced support for working with Markdown files. It brings multiple features to make editing, previewing, and managing Markdown content easier.
   - Features:
     - Live preview of Markdown content.
     - Table of contents generation.
     - Enhanced syntax highlighting.
     - Keyboard shortcuts for common Markdown actions.
     - Auto-formatting and linting for clean Markdown syntax.
</details>

<details>
  <summary><a href=https://marketplace.visualstudio.com/items?itemName=ms-python.python>Python</a></summary>
  
  The Python extension is essential for working with Python code in VS Code. It provides a range of features to help you develop and manage Python applications with ease. Support for the Python language (for all actively supported Python versions), providing access points for extensions to seamlessly integrate and offer support for IntelliSense (Pylance), debugging (Python Debugger), formatting, linting, code navigation, refactoring, variable explorer, test explorer, and more!
  - Features:
    - IntelliSense for code completion, method signatures, and more.
    - Code linting, debugging, and testing support.
    - Jupyter notebook integration for running Python code interactively.
    - Python environment management and virtual environment support.
    - Refactoring tools and code navigation.
</details>

<details>
  <summary><a href=https://marketplace.visualstudio.com/items?itemName=4ops.terraform>Terraform</a></summary>
  
  The Terraform extension for VS Code is designed to help developers write, manage, and deploy Terraform configuration files with ease. It offers syntax highlighting, autocompletion, linting, and other essential features to improve the Terraform development experience within the Visual Studio Code editor.
  - Features:
    - Provides syntax highlighting for .tf and .tfvars files to make the code easier to read.
    - Offers autocompletion for resources, variables, and functions to speed up the development process.
    - Provides predefined code snippets for common Terraform configurations.
    - Enables quick access to Terraform commands directly from the VS Code interface.
    - Offers basic linting to catch errors in your Terraform code as you write.
    - Automatically formats your Terraform code according to standard conventions.
    - Works with Terraform CLI commands, allowing you to execute them from within VS Code.
</details>

<details>
  <summary><a href=https://marketplace.visualstudio.com/items?itemName=HashiCorp.terraform>Terraform [HashiCorp]</a></summary>
  
   The HashiCorp Terraform extension, developed by HashiCorp, provides rich integration and support for Terraform within Visual Studio Code. This extension is the official Terraform extension from HashiCorp, offering enhanced features specifically optimized for working with Terraform configurations.
   - Features:
     - Provides robust support for the Terraform language, including advanced syntax highlighting, autocompletion, and validation.
     - Run terraform plan and terraform apply commands directly from VS Code with integrated output.
     - Integrates Terraform documentation into the editor to quickly reference resource attributes, syntax, and best practices.
     - Automatically formats Terraform files using the terraform fmt tool, maintaining clean and consistent code.
     - Provides linting and validation for Terraform configuration files to help catch potential issues early in development.
     - Integrates with the workspace settings to allow you to define the Terraform working environment directly within VS Code.
     - Offers intelligent code completion and validation based on the Terraform providers and resources in your code.
</details>

<details>
  <summary><a href="https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml">Yaml</a></summary>
  
  The YAML extension for VS Code provides support for editing YAML files, which are commonly used for configuration files, data serialization, and Kubernetes manifests.
  - Features:
    - Syntax highlighting for YAML files.
    - Autocompletion for keys and values.
    - Validation and linting to catch syntax errors.
    - YAML schema support for validation against predefined rules.
</details>


<details>
  <summary>Others</summary>
  
  Some nice and funny extensions 😜
  - [vscode-pets](https://marketplace.visualstudio.com/items?itemName=tonybaloney.vscode-pets)
    
    Fun and lighthearted extension for Visual Studio Code that adds an interactive "pet" to your editor. It’s designed to bring a little joy to your workspace and make coding a bit more fun. 🐾
  - [In your Face](https://marketplace.visualstudio.com/items?itemName=TTOOWA.in-your-face-incredible)

    Fun and motivational tool designed to give you instant feedback—sometimes a bit too much feedback! It adds a quirky twist to your coding experience by showing pop-ups or messages in your face to keep you focused, motivated, or entertained while you work.
</details>



### Contributing 🤝

Found a great tool or extension that isn't listed here? Contributions are always welcome! Feel free to submit a pull request or open an issue to share your favorite DevOps tools or VS Code extensions.

### Feedback & Suggestions 💬

If you have ideas for improving this list or would like to see specific categories/tools covered, let me know! Your feedback helps make this resource even better.

### Closing Thoughts 🚀

DevOps is all about collaboration, automation, and continuous improvement. This repository is here to help you discover tools that can make your workflows faster, easier, and more efficient. Explore, experiment, and let these tools empower you to build amazing things.

Happy coding! 🎉
