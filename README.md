<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/140833078-77973dcf-d3a6-421f-b6a7-b6e63fb1e97c.png">
  <br />
  VS Code Guide
</h1>

#### A guide covering VS Code including the applications, libraries and tools that will make you a better and more efficient with VS Code development.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832423-bfcb9526-db0d-4900-b84b-49d75ce1d0df.png">
<br />
</p>

# Table of Contents

1. [Getting Started](https://github.com/mikeroyal/VSCode-Guide#getting-started)

    - [VS Code Extensions for Developer Productivity](https://github.com/mikeroyal/VSCode-Guide#VS-Code-Extensions-for-Developer-Productivity)

2. [Azure Development](https://github.com/mikeroyal/VSCode-Guide#azure-development)

3. [AWS Development](https://github.com/mikeroyal/VSCode-Guide#aws-development)

4. [Google Cloud Development](https://github.com/mikeroyal/VSCode-Guide#google-cloud-development)

5. [Kubernetes](https://github.com/mikeroyal/VSCode-Guide#kubernetes)

6. [Docker](https://github.com/mikeroyal/VSCode-Guide#docker)

7. [Ansible](https://github.com/mikeroyal/VSCode-Guide#Ansible)

8. [Terraform](https://github.com/mikeroyal/VSCode-Guide#Terraform)

9. [Windows Subsystem for Linux (WSL)](https://github.com/mikeroyal/VSCode-Guide#windows-subsystem-for-linux-wsl)

10. [GraphQL Development](https://github.com/mikeroyal/VSCode-Guide#graphql-development)

11. [.NET Development](https://github.com/mikeroyal/VSCode-Guide#net-development)

12. [C# Development](https://github.com/mikeroyal/VSCode-Guide#c-development)

13. [F# Development](https://github.com/mikeroyal/VSCode-Guide#f-development)

14. [Xamarin Development](https://github.com/mikeroyal/VSCode-Guide#Xaramin-Development)

15. [PowerShell Development](https://github.com/mikeroyal/VSCode-Guide#powershell-development)

16. [TypeScript Development](https://github.com/mikeroyal/VSCode-Guide#typescript-development)

17. [JavaScript Development](https://github.com/mikeroyal/VSCode-Guide#javascript-development)

18. [React Development](https://github.com/mikeroyal/VSCode-Guide#react-development)

19. [Ionic Development](https://github.com/mikeroyal/VSCode-Guide#ionic-development)

20. [Cordova Development](https://github.com/mikeroyal/VSCode-Guide#cordova-development)

21. [Angular Development](https://github.com/mikeroyal/VSCode-Guide#angular-development)

22. [Vue.js Development](https://github.com/mikeroyal/VSCode-Guide#vuejs-development)

23. [Svelte Development](https://github.com/mikeroyal/VSCode-Guide#svelte-development)

24. [Node.js Development](https://github.com/mikeroyal/VSCode-Guide#nodejs-development)

25. [jQuery Development](https://github.com/mikeroyal/VSCode-Guide#jquery-development)

26. [ElectronJS Development](https://github.com/mikeroyal/VSCode-Guide#electron-development)

27. [C/C++ Development](https://github.com/mikeroyal/VSCode-Guide#cc-development)

28. [Java Development](https://github.com/mikeroyal/VSCode-Guide#java-development)

29. [Kotlin Development](https://github.com/mikeroyal/VSCode-Guide#kotlin-development)

30. [Clojure Development](https://github.com/mikeroyal/VSCode-Guide#clojure-development)

31. [Python Development](https://github.com/mikeroyal/VSCode-Guide#python-development)

32. [R Development](https://github.com/mikeroyal/VSCode-Guide#r-development)

33. [Rust Development](https://github.com/mikeroyal/VSCode-Guide#rust-development)

34. [Go Development](https://github.com/mikeroyal/VSCode-Guide#go-development)

35. [Swift Development](https://github.com/mikeroyal/VSCode-Guide#swift-development)

36. [Ruby Development](https://github.com/mikeroyal/VSCode-Guide#ruby-development)

37. [PHP Development](https://github.com/mikeroyal/VSCode-Guide#php-development)

38. [Flutter Development](https://github.com/mikeroyal/VSCode-Guide#flutter-development)

39. [Networking](https://github.com/mikeroyal/VSCode-Guide#networking)

40. [Databases](https://github.com/mikeroyal/VSCode-Guide#databases)

# Getting Started
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

[Visual Studio Code](https://code.visualstudio.com) is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832435-49e53589-e9e1-47fe-a1bd-d9800cfc1274.png">
<br />
VS Code
</p>

[Visual Studio Marketplace](https://marketplace.visualstudio.com/VSCode) is a marketplace for all extensions for Visual Studio, Azure DevOps Services, Azure DevOps Server and Visual Studio Code.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832440-0247a088-4eeb-4c57-ae7d-90894d56d629.png">
<br />
VS Code Marketplace
</p>


[VS Code Documentation](https://code.visualstudio.com/docs)

[Working with GitHub in VS Code](https://code.visualstudio.com/docs/editor/github)

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code. Also, from any repo or pull request on GitHub you can simply press the period (.) key on your keyboard to bring up the browser-based VS Code environment with the source code file ready for editing. That dot (.) press to bring up the web-based VS Code editor takes you to https://github.dev/.

[Language Server Protocol (LSP)](https://microsoft.github.io/language-server-protocol/) is a tool that defines the protocol used between an editor or IDE and a language server that provides language features like auto complete, go to definition, find all references.

### VS Code Extensions for Developer Productivity

[Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/) is a service/ extension that enables you to collaboratively edit and debug with others in real time, regardless of the programming languages you're using or app types you're building. You can instantly and securely share your current project, start a joint debugging session, share terminal instances, forward localhost web apps, have voice calls, and more.

[GistPad](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs) is a Visual Studio Code extension that allows you to edit GitHub Gists and repositories from the comfort of your favorite editor. You can open, create, delete, fork and star gists and repositories, and then seamlessly begin editing files as if they were local, without ever cloning, pushing or pulling anything.

[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) is an extension for Visual Studio Code that launches a development local Server with live reload feature for static & dynamic pages.

[GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) is an extension for Visual Studio Code that allows you to review and manage GitHub pull requests and issues in Visual Studio Code.

[Terminal](https://marketplace.visualstudio.com/items?itemName=formulahendry.terminal) is an extension for Visual Studio Code that lets you run terminal command directly in the Editor.

[Profile Switcher](https://marketplace.visualstudio.com/items?itemName=aaronpowell.vscode-profile-switcher) is an extension for Visual Studio Code that allows you to switch between different profiles you have created.

[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) is an extension for Visual Studio Code that gets the Material Design icons into your VS Code.

[One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) is an extension for Visual Studio Code that adds Atom's iconic One Dark theme, which is one of the most installed themes for VS Code.

[VSCode Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) is an extension for Visual Studio Code that brings icons to your Visual Studio Code setup.

[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) is an extension for Visual Studio Code that helps you visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more.

[Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) is an extension for Visual Studio Code that will display inline in the editor the size of the imported/required package. The extension utilizes webpack with babili-webpack-plugin in order to detect the imported size.

[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) is an extension for Visual Studio Code that gives you everything you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more).

[Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer) is an extension for Visual Studio Code that allows matching brackets to be identified with colours. The user can define which characters to match, and which colours to use.

[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) is an extension for Visual Studio Code that automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text.

[Auto-Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) is an extension for Visual Studio Code that automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text does.

[Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) is an extension for Visual Studio Code that synchronizes Settings, Snippets, Themes, File Icons, Launch, Keybindings, Workspaces and Extensions Across Multiple Machines Using GitHub Gist.

[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) is an extension for Visual Studio Code that lets you mark lines of code and jump to them.

[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) is an extension for Visual Studio Code that improves your code commenting by annotating with alert, informational, TODOs, and more.

[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) is an extension for Visual Studio Code that works as a spelling checker for source code.

[CSS Peak](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek) is an extension for Visual Studio Code that allows peeking to css ID and class strings as definitions from html files to respective CSS. It also allows peek and goto definition.

[Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) is an extension for Visual Studio Code that enhances the Tailwind development experience by providing Visual Studio Code users with advanced features such as autocomplete, syntax highlighting, and linting.

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) is an extension for Visual Studio Code that is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

[NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) is an extension for Visual Studio Code that autocompletes npm modules in import statements.

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) is an extension for Visual Studio Code that autocompletes filenames.

[Relative Path](https://marketplace.visualstudio.com/items?itemName=jakob101.RelativePath) is an extension for Visual Studio Code that gets the relative url paths from files in the current workspace.

[Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete) is an extension for Visual Studio Code that provides path completion for visual studio code.

[Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode) is an extension for Visual Studio Code that updates your discord status with a rich presence.

[Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) is an extension for Visual Studio Code that runs code snippets or code files for multiple languages: C/C++, Java, JavaScript, PHP, Python, Perl, Ruby, Go, Lua, Groovy, PowerShell, BASH/SH, C#, F#, .NET Core, TypeScript, CoffeeScript, Scala, Swift, Julia, OCaml, R, Elixir, Clojure, Haxe, Objective-C, Rust, Racket, Scheme, Kotlin, Dart, Haskell, Nim, D, CUDA, and custom command.

[Kite](https://marketplace.visualstudio.com/items?itemName=kiteco.kite) is an extension for Visual Studio Code that provides an AI-powered programming assistant that helps you write code faster inside Visual Studio Code. Kite works for all major programming languages: Python, Java, Go, PHP, C/C#/C++, Javascript, HTML/CSS, Typescript, React, Ruby, Scala, Kotlin, Bash, Vue and React.

[Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) is an extension for Visual Studio Code that provides an AI code completion tool trusted by millions of developers to code faster with fewer errors. Whether you are a new dev or a seasoned pro, working solo or part of a team, Tabnine will help push your productivity to new heights while cutting your QA time in your favorite IDE.


# Azure Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118413013-01e09100-b652-11eb-95a9-fdb664687470.png">
  <br />
</p>

**[Visual Studio Code Azure Extensions](https://code.visualstudio.com/docs/azure/extensions)**

## Azure Learning Resources

[Microsoft Azure](https://azure.microsoft.com/en-us/) is a cloud computing service created by Microsoft for building, testing, deploying, and managing applications and services through Microsoft-managed data centers.

[Get started with Azure](https://azure.microsoft.com/en-us/get-started/)

[Azure Demo and Q&A](https://azure.microsoft.com/en-us/get-started/webinar/)

[Microsoft Azure Training & Certification Courses](https://www.microsoft.com/en-us/learning/azure-training-certification.aspx)

[Azure on Microsoft Learn](https://docs.microsoft.com/en-us/learn/azure/)

[Microsoft Certified: Azure Fundamentals](https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/)

[Microsoft Certified: DevOps Engineer Expert Cert.](https://docs.microsoft.com/en-us/learn/certifications/devops-engineer)

[Introduction to Azure DevOps from A Cloud Guru](https://acloud.guru/learn/introduction-to-azure-devops)

[Microsoft Certified: Azure IoT Developer Specialty](https://docs.microsoft.com/en-us/learn/certifications/azure-iot-developer-specialty)

[Microsoft Certified: Azure Security Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-security-engineer)

[Microsoft Azure Certification Training Courses on Udemy](https://www.udemy.com/topic/microsoft-azure/)

[Free Microsoft Azure Courses & Tutorials on Udemy](https://www.udemy.com/topic/microsoft-azure/free/)

[Microsoft Azure Certification Training Courses on Coursera](https://www.coursera.org/learn/cloud-azure-intro)

[Microsoft Azure Certification Training Courses on edX](https://www.edx.org/learn/azure)

## Azure Tools

[Microsoft Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/)

[Azure command-line interface (Azure CLI)](https://docs.microsoft.com/en-us/cli/azure/) is a command line that provides a set of commands used to create and manage Azure resources.

[Visual Studio Code](https://code.visualstudio.com/docs/azure/extensions) is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).

[Azure Functions](https://azure.microsoft.com/en-us/services/functions/) is a solution for easily running small pieces of code, or "functions," in the cloud. You can write just the code you need for the problem at hand, without worrying about a whole application or the infrastructure to run it.

[Azure DevOps](https://azure.microsoft.com/en-us/services/devops/?nav=min) is a set of services for teams to share code, track work, and ship software; CLIs Build, deploy, diagnose, and manage multi-platform, scalable apps and services; Azure Pipelines Continuously build, test, and deploy to any platform and cloud; Azure Lab Services Set up labs for classrooms, trials, development and testing, and other scenarios.

[Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/what-is-azure-data-studio?view=sql-server-ver15) is a cross-platform database tool for data professionals using on-premises and cloud data platforms on Windows, macOS, and Linux. It offers a modern editor experience with IntelliSense, code snippets, source control integration, and an integrated terminal. It's engineered with the data platform user in mind, with built-in charting of query result sets and customizable dashboards.

[Azure Active Directory (Azure AD)](https://azure.microsoft.com/en-us/services/active-directory/) is Microsoft's cloud-based identity and access management service, which helps your employees sign in and access resources in: External resources, such as Microsoft 365, the Azure portal, and thousands of other SaaS applications.

[Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/overview) is a client tool that helps you maximize the availability and performance of your applications and services. It delivers a comprehensive solution for collecting, analyzing, and acting on telemetry from your cloud and on-premises environments.

[Azure Cognitive Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/) is a set of cloud-based services with REST APIs and client library SDKs available to help you build cognitive intelligence into your applications. You can add cognitive features to your applications without having artificial intelligence (AI) or data science skills. All it takes is an API call to embed the ability to see, hear, speak, search, understand, and accelerate decision-making into your apps.

[Azure Data Lake Storage](https://azure.microsoft.com/en-us/solutions/data-lake/) is a storage repository that holds a large amount of data in its native, raw format. Data lake stores are optimized for scaling to terabytes and petabytes of data. The data typically comes from multiple heterogeneous sources, and may be structured, semi-structured, or unstructured.

[Azure Service Fabric](https://azure.microsoft.com/en-us/services/service-fabric/) is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable microservices and containers. Service Fabric also addresses the significant challenges in developing and managing cloud native applications. It powers core Azure infrastructure as well as other Microsoft services such as Skype for Business, Intune, Azure Event Hubs, Azure Data Factory, Azure Cosmos DB, Azure SQL Database, Dynamics 365, and Cortana.

[Microsoft Azure Storage Emulator](https://docs.microsoft.com/en-us/azure/storage/common/storage-use-emulator) is a tool that emulates the Azure Blob, Queue, and Table services for local development purposes. You can test your application against the storage services locally without creating an Azure subscription or incurring any costs.

[Azure Cosmos DB Emulator](https://docs.microsoft.com/en-us/azure/cosmos-db/local-emulator?tabs=cli,ssl-netstd21) is a tool that provides a local environment that emulates the Azure Cosmos DB service for development purposes. Using the Azure Cosmos DB Emulator, you can develop and test your application locally, without creating an Azure subscription or incurring any costs.

[Microsoft Azure Storage Explorer](https://www.storageexplorer.com/) is a standalone app that makes it easy to work with Azure Storage data on Windows, macOS, and Linux.

[Azure BatchExplorer](https://github.com/Azure/BatchExplorer#batchexplorer) is a  client tool to help create, debug and monitor Azure Batch Applications.

[Azure Key Vault Explorer](https://github.com/microsoft/AzureKeyVaultExplorer/blob/master/README.md)  is a  client tool to help be productive when working with secrets.

[Azurite](https://github.com/Azure/Azurite/blob/master/README.md) is an open source Azure Storage API compatible server (emulator). Based on Node.js, Azurite provides cross platform experiences for customers wanting to try Azure Storage easily in a local environment. Azurite simulates most of the commands supported by Azure Storage with minimal dependencies.

[Azure Cloud Shell](https://shell.azure.com/) is an interactive, authenticated, browser-accessible shell for managing Azure resources. It provides the flexibility of choosing the shell experience that best suits the way you work, either Bash or PowerShell.

[Azure Lab Services](https://azure.microsoft.com/en-us/services/lab-services/) is an easy to set up and provide on-demand access to preconfigured virtual machines (VMs) to support your scenarios. Teach a class, train professionals, run a hackathon or a hands-on lab, and more.

[Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/) is a cloud-hosted pipelines for Linux, macOS, and Windows. Where you can build web, desktop and mobile applications. Deploy to any cloud or on‑premises.

[Azure Bots Service](https://azure.microsoft.com/en-us/services/bot-services/) is a service that develops intelligent, enterprise-grade bots that help you enrich the customer experience while maintaining control of your data. Build any type of bot—from a Q&A bot to your own branded virtual assistant—to quickly connect your users to the answers they need.

[Azure PlayFab](https://azure.microsoft.com/en-us/services/playfab/) is a service that enables developers to use the intelligent cloud to build and operate games, analyze gaming data and improve overall gaming experiences. Along with the Microsoft Game Stack that includes platforms, tools, and services like Visual Studio, DirectX, Havok, and Xbox.

[Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) is a tool that makes it fast, easy, and collaborative Apache Spark-based analytics platform. Azure Databricks, set up your Apache Spark™ environment in minutes, autoscale, and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

[Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/) is an enterprise-grade machine learning service to build and deploy models faster. It empowers data scientists and developers with a wide range of productive experiences to build, train, and deploy machine learning models and foster team collaboration. Accelerate time to market with industry-leading MLOps—DevOps for machine learning. Innovate on a secure, trusted platform, designed for responsible machine learning.

[Azure Open Datasets](https://azure.microsoft.com/en-us/services/open-datasets/) is a tool that curates open data made easily accessible on Azure.

[Azure Percept](https://azure.microsoft.com/en-us/services/azure-percept/) is a comprehensive, easy-to-use platform with added security for creating edge AI solutions.

[Azure Data Share](https://azure.microsoft.com/en-us/services/data-share/) is a simple and safe service for sharing big data. It  provides full visibility into your data sharing relationships with a user-friendly interface. Share data in just a few clicks, or build your own application using the REST API.

[Azure Data Factory](https://azure.microsoft.com/en-us/services/data-factory/) is a fully managed, serverless data integration solution for ingesting, preparing, and transforming all your data at scale.

[Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) is a limitless analytics service that brings together data integration, enterprise data warehousing, and big data analytics. It gives you the freedom to query data on your terms, using either serverless or dedicated resources at scale.

[Azure HDInsight](https://azure.microsoft.com/en-us/services/hdinsight/) is an enterprise-ready, managed cluster service for open-source analytics.It let's you run popular open-source frameworks including Apache Hadoop, Spark, Hive, Kafka, and more.

[Azure Blockchain Service](https://azure.microsoft.com/en-us/services/blockchain-service/) is a service that simplifies the formation, management, and governance of consortium blockchain networks so you can focus on business logic and app development.

[Azure Logic Apps](https://azure.microsoft.com/en-us/services/logic-apps/) is a leading integration platform as a service (iPaaS) enables key enterprise scenarios for developers. Built on a containerized runtime that increases scale and portability while automating business-critical workflows anywhere.

[Azure Quantum](https://azure.microsoft.com/en-us/services/quantum/) is an innovative quantum computing and optimization solutions converge in a single marketplace quantum service.

[Azure VMware Solution](https://azure.microsoft.com/en-us/services/azure-vmware/) is a service that seamlessly moves VMware-based workloads from your datacenter to Azure and integrate your VMware environment with Azure. Keep managing your existing environments with the same VMware tools you already know while you modernize your applications with Azure native services.

[Azure Spring Cloud](https://azure.microsoft.com/en-us/services/spring-cloud/) is a fully managed Spring Cloud service, jointly built and operated with VMware.

[Azure CycleCloud](https://azure.microsoft.com/en-us/features/azure-cyclecloud/) is a serviece that creates, manages, operates, and optimizes HPC and big compute clusters of any scale.

[Azure API Apps](https://azure.microsoft.com/en-us/services/app-service/api/) is a service that quickly builds and consumes APIs in the cloud using the language of your choice.

[Azure Web Apps](https://azure.microsoft.com/en-us/services/app-service/web/) is an easy way to create and deploy mission-critical web applications that scale with your business.

[Windows Virtual Desktop](https://azure.microsoft.com/en-us/services/virtual-desktop/) is a service that enables a secure, remote desktop experience from anywhere.

[VMware Horizon Cloud on Microsoft Azure](https://azure.microsoft.com/en-us/services/virtual-desktop/vmware-horizon-cloud/) is a desktop virtualization service available in Azure Marketplace. Simplify your delivery of on-premises and cloud virtual desktops and applications by connecting your instance of Azure to VMware.

[Citrix Virtual Apps and Desktops for Azure](https://azure.microsoft.com/en-us/services/virtual-desktop/citrix-virtual-apps-desktops-for-azure/) is a desktop and app virtualization service available through Azure Marketplace or agreements with Citrix. Use familiar tools to manage on-premises Citrix deployments alongside Windows Virtual Desktop on Azure, supporting cloud modernization while maximizing your existing investment.

[Azure Container Registry](https://azure.microsoft.com/en-us/services/container-registry/) is a registry of Docker and Open Container Initiative (OCI) images, with support for all OCI artifacts.

[Azure Web App for Containers](https://azure.microsoft.com/en-us/services/app-service/containers/) is an easily deploy and run containerized applications on Windows and Linux.

[Azure SQL Edge](https://azure.microsoft.com/en-us/services/sql-edge/) is a service that makes a small-footprint, edge-optimized SQL database engine with built-in AI. This productivity tool for edge computing combines new capabilities such as data streaming and time series with in-database machine learning and graph features. Develop your application once and deploy anywhere across the edge, your datacenter, and Azure.

[Azure Arc](https://azure.microsoft.com/en-us/services/azure-arc/) is a service that offers simplified management, faster app development, and consistent Azure services. Standardize visibility, operations, and compliance across a wide range of resources and locations by extending the Azure control plane. Build cloud-native apps anywhere, at scale.

[Azure Artifacts](https://azure.microsoft.com/en-us/services/devops/artifacts/) is a services that provides fully integrated package management to your continuous integration/continuous delivery (CI/CD) pipelines with a single click. Create and share Maven, npm, NuGet, and Python package feeds from public and private sources with teams of any size.

[Azure Boards](https://azure.microsoft.com/en-us/services/devops/boards/) is a service that helps you plan, track, and discuss work across your teams. It let's you track work with Kanban boards, backlogs, team dashboards, and custom reporting.

[Azure ExpressRoute](https://azure.microsoft.com/en-us/services/expressroute/) is a tool that helps you experience a faster, private connection to Azure.

[Azure Sentinel](https://azure.microsoft.com/en-us/services/azure-sentinel/) is your birds-eye view across the enterprise. It uses the cloud and large-scale intelligence from decades of Microsoft security experience to work. Making your threat detection and response smarter and faster with artificial intelligence (AI).

[Azure Stack](https://azure.microsoft.com/en-us/overview/azure-stack/) is a service that builds and runs hybrid apps across datacenters, edge locations, remote offices, and the cloud.

[Azure Stack HCI](https://azure.microsoft.com/en-us/products/azure-stack/hci/) is a new hyperconverged infrastructure (HCI) operating system delivered as an Azure service that provides the latest security, performance, and feature updates. Deploy and run Windows and Linux virtual machines (VMs) in your datacenter or at the edge using your existing tools, processes, and skill sets.

[Azure Sphere](https://azure.microsoft.com/en-us/services/azure-sphere/) is a comprehensive IoT security solution including hardware (crossover microcontroller), OS, and cloud components for IoT device security to actively protect your devices, your business, and your customers.

[Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) is a service that provides a cloud-hosted solution back end to connect virtually any device. Extend your solution from the cloud to the edge with per-device authentication, built-in device management, and scaled provisioning.

[Azure IoT Edge](https://azure.microsoft.com/en-us/services/iot-edge/) is a fully managed service built on Azure IoT Hub. Deploy your cloud workloads—artificial intelligence, Azure and third-party services, or your own business logic to run on Internet of Things (IoT) edge devices via standard containers.

[Azure Lighthouse](https://azure.microsoft.com/en-us/services/azure-lighthouse/) is a secure managed services and access control for partners and customers.

[Azure Backup](https://azure.microsoft.com/en-us/services/backup/) is a cost-effective, secure, one-click backup solution that’s scalable based on your backup storage needs. The centralized management interface makes it easy to define backup policies and protect a wide range of enterprise workloads, including Azure Virtual Machines, SQL and SAP databases, and Azure file shares.

[Azure Resource Manager](https://azure.microsoft.com/en-us/features/resource-manager/) is a tool that enables you to repeatedly deploy your app and have confidence your resources are deployed in a consistent state. You define the infrastructure and dependencies for your app in a single declarative template. This template is flexible enough to use for all of your environments such as test, staging or production.

[Azure Automanage](https://azure.microsoft.com/en-us/services/azure-automanage/) is a tool that implifies IT management with optimized, automated operations across the entire lifecycle of dev/test and production virtual machines (VMs).

[Azure Network Watcher](https://azure.microsoft.com/en-us/services/network-watcher/) is a tool that monitors, diagnoses, and gains insights to your network performance and health.

[Azure Resource Mover](https://azure.microsoft.com/en-us/services/resource-mover/) is a that that Simplifies how you move multiple resources between Global Azure regions.

[Azure Bastion](https://azure.microsoft.com/en-us/services/azure-bastion/) is a fully managed PaaS service that provides secure and seamless RDP and SSH access to your virtual machines directly through the Azure Portal. Azure Bastion is provisioned directly in your Virtual Network (VNet) and supports all VMs in your Virtual Network (VNet) using SSL without any exposure through public IP addresses.

[Azure Load balancing](https://azure.microsoft.com/en-us/products/azure-load-balancing/) is a service that instantly scale your applications with Azure load balancing services for high availability and high performance. Get started with a quick needs assessment and load balancing recommendation—using the service selection tool.

[Azure Orbital](https://azure.microsoft.com/en-us/services/orbital/) is a Ground Station As-a-Service that provides communication and control of your satellite. Orbital enables easy and integrated data processing and scale for your operations directly from Azure. Leverage familiar Azure services to process and store your data at scale.

[Azure Route Server](https://azure.microsoft.com/en-us/services/route-server/) is a tool that enables network appliances to exchange route information with Azure virtual networks dynamically. Configure your network appliances and Azure ExpressRoute and VPN gateways to automatically take the latest route information from Azure Route Server instead of manually talking to each network.

[Azure VPN Gateway](https://azure.microsoft.com/en-us/services/vpn-gateway/) is a service that connects your on-premises networks to Azure through Site-to-Site VPNs in a similar way that you set up and connect to a remote branch office. The connectivity is secure and uses the industry-standard protocols Internet Protocol Security (IPsec) and Internet Key Exchange (IKE).

[Microsoft Azure Attestation](https://azure.microsoft.com/en-us/services/azure-attestation/) is a unified solution for remotely verifying the trustworthiness of a platform and integrity of the binaries running inside it. Azure Attestation receives evidence from the platform, validates it with security standards, evaluates it against configurable policies, and produces an attestation token for claims-based applications. The service supports attestation of trusted platform modules (TPMs) and trusted execution environments (TEEs) like Intel® Software Guard Extensions (SGX) and virtualization-based security (VBS) enclaves.

[Azure Data Box](https://azure.microsoft.com/en-us/services/databox/) is a device that easily moves data to Azure when busy networks aren’t an option. Move large amounts of data to Azure when you're limited by time, network availability, or costs, using common copy tools such as Robocopy. All data is AES-encrypted, and the devices are wiped clean after upload, in accordance with NIST Special Publication 800-88 revision 1 standards.

[Azure Blob Storage](https://azure.microsoft.com/en-us/services/storage/blobs/) is a massively scalable and secure object storage for cloud-native workloads, archives, data lakes, high-performance computing, and machine learning.

[PowerShell/PowerShell Core](https://docs.microsoft.com/en-us/powershell/) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models. It includes a command-line shell, an associated scripting language and a framework for processing cmdlets.

[Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/) creates virtual machines on Windows 10. Hyper-V can be enabled in many ways including using the Windows 10 control panel, PowerShell or using the Deployment Imaging Servicing and Management tool (DISM).

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code.

[GitHub Actions](https://docs.github.com/en/actions) will automate, customize, and execute your software development workflows right in your repository with GitHub Actions. You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.[GitHub Actions for Azure](https://docs.microsoft.com/en-us/azure/developer/github/github-actions) you can create workflows that you can set up in your repository to build, test, package, release and deploy to Azure.

# AWS Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/114322508-7d8c7280-9ad5-11eb-807e-4dc63c9bc0e1.png">
  <br />
</p>

**[AWS Toolkit for Visual Studio Code](https://aws.amazon.com/visualstudiocode/)**

## AWS Learning Resources

[Amazon Web Services](https://aws.amazon.com/about-aws/) is a reliable, scalable, and inexpensive on-demand cloud computing platforms, services and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis.

[AWS Training and Certification](https://aws.amazon.com/training/)

[Getting Started with Amazon Web Services (AWS)](https://aws.amazon.com/getting-started/)

[Hands-On Tutorials for Amazon Web Services (AWS)](https://aws.amazon.com/getting-started/hands-on/

[Getting started with AWS IoT Core ](https://docs.aws.amazon.com/iot/latest/developerguide/iot-gs.html)

[AWS Academy - Amazon Web Services (AWS)](https://aws.amazon.com/training/awsacademy/)

[AWS Educate](https://aws.amazon.com/education/awseducate/)

[Architecting on AWS Classroom Training](https://aws.amazon.com/training/classroom/architecting-on-aws/)

[DevOps Engineering on AWS from AWS Training](https://aws.amazon.com/training/course-descriptions/devops-engineering/)

[AWS Certified DevOps Engineer - Professional from A Cloud Guru](https://acloud.guru/learn/aws-certified-devops-engineer-professional)

[AWS Internet of Things Foundation Series Training](https://www.aws.training/Details/Curriculum?id=27289)

[AWS Certified Security - Specialty Certification](https://aws.amazon.com/certification/certified-security-specialty/)

[AWS Certification Training Courses on Udemy](https://www.udemy.com/topic/aws-certification/)

[Amazon Web Services Courses on Coursera](https://www.coursera.org/aws)

[Amazon Web Services Courses on edX](https://www.edx.org/school/aws)

## AWS Tools

[AWS Pricing Calculator](https://calculator.aws/)

[AWS Marketplace](https://aws.amazon.com/) is a digital catalog with thousands of software listings from independent software vendors that make it easy to find, test, buy, and deploy software that runs on AWS.

[AWS Cloud9](https://aws.amazon.com/cloud9/) is a cloud-based integrated development environment (IDE) that lets you write, run, and debug your code with just a browser. It includes a code editor, debugger, and terminal. Cloud9 comes prepackaged with essential tools for popular programming languages, including JavaScript, Python, PHP, and more, so you don’t need to install files or configure your development machine to start new projects.

[AWS Command Line Interface (CLI)](https://aws.amazon.com/cli/) is a unified tool to manage your AWS services through the command line interface.

[AWS Amplify Command Line Interface (CLI)](https://docs.amplify.aws/cli) is a unified toolchain to create, integrate, and manage the AWS cloud services for your app.

[AWS Serverless Application Model (SAM) CLI](https://github.com/aws/aws-sam-cli) is a command line tool for an open-source framework for building serverless applications. It provides shorthand syntax to express functions, APIs, databases, and event source mappings. With just a few lines of configuration, you can define the application you want and model it.

[AWS Copilot command line interface (CLI)](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Copilot.html) is a command line tool that simplifies building, releasing, and operating production-ready containerized applications on Amazon ECS from a local development environment. The AWS Copilot CLI aligns with developer workflows that support modern application best practices: from using infrastructure as code to creating a CI/CD pipeline provisioned on behalf of a user.

[Amazon Elastic Container Service (Amazon ECS) command line interface (CLI)](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS_CLI.html) is a command line tool that  provides high-level commands to simplify creating, updating, and monitoring clusters and tasks from a local development environment. The Amazon ECS CLI supports Docker Compose files, a popular open-source specification for defining and running multi-container applications.

[AWS ECS](https://aws.amazon.com/ecs/) is a highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS. Amazon ECS eliminates the need for you to install and operate your own container orchestration software, manage and scale a cluster of virtual machines, or schedule containers on those virtual machines.

[Amazon Simple Storage Service (Amazon S3)](https://aws.amazon.com/s3/) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as data lakes, websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics.

[AWS Cloud Development Kit (AWS CDK)](https://aws.amazon.com/cdk/) is an open-source software development framework to define cloud infrastructure in code and provision it through AWS CloudFormation. It offers a high-level object-oriented abstraction to define AWS resources imperatively using the power of modern programming languages.

[AWS Lambda](https://aws.amazon.com/lambda/) is an event-driven, serverless computing platform provided by Amazon as a part of the Amazon Web Services. It is a computing service that runs code in response to events and automatically manages the computing resources required by that code.

[AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) is an easy-to-use service for deploying and scaling web applications and services developed with Java,.NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS.

[AWS IoT Greengrass](https://aws.amazon.com/greengrass/) is an Internet of Things (IoT) open source edge runtime and cloud service that helps you build, deploy, and manage device software. It is used for IoT applications on millions of devices in homes, factories, vehicles, and businesses.

[AWS CodeArtifact](https://aws.amazon.com/codeartifact/) is a fully managed artifact repository service that makes it easy for organizations of any size to securely store, publish, and share software packages used in their software development process. CodeArtifact can be configured to automatically fetch software packages and dependencies from public artifact repositories so developers have access to the latest versions.

[AWS CodeCommit](https://aws.amazon.com/codecommit/) is a fully-managed source control service that hosts secure Git-based repositories. It makes it easy for teams to collaborate on code in a secure and highly scalable ecosystem. CodeCommit eliminates the need to operate your own source control system or worry about scaling its infrastructure.

[AWS CodePipeline](https://aws.amazon.com/codepipeline/) is a fully managed [continuous delivery](https://aws.amazon.com/devops/continuous-delivery/) service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define. This enables you to rapidly and reliably deliver features and updates. You can easily integrate AWS CodePipeline with third-party services such as GitHub or with your own custom plugin.

[AWS CodeStar](https://aws.amazon.com/codestar/) is a unified user interface, enabling you to easily manage your software development activities in one place. With AWS CodeStar, you can set up your entire [continuous delivery](https://aws.amazon.com/devops/continuous-delivery/) toolchain in minutes, allowing you to start releasing code faster.

[AWS X-Ray](https://aws.amazon.com/xray/) is a tool that traces user requests as they travel through your entire application. It aggregates the data generated by the individual services and resources that make up your application, providing you an end-to-end view of how your application is performing. It helps developers analyze and debug production, distributed applications, such as those built using a microservices architecture.

[AWS CodeDeploy](https://aws.amazon.com/codedeploy/) is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during application deployment, and handles the complexity of updating your applications.

[AWS CodeBuild](https://aws.amazon.com/codebuild/) is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. With CodeBuild, you don't need to provision, manage, and scale your own build servers.

[Red Hat OpenShift Service on AWS (ROSA)](https://www.openshift.com/products/amazon-openshift) is a fully-managed and jointly supported Red Hat OpenShift offering that combines the power of Red Hat OpenShift, the industry's most comprehensive enterprise Kubernetes platform, and the AWS public cloud.

[Amazon API Gateway](https://aws.amazon.com/api-gateway/) is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.

[AWS Storage Gateway](https://aws.amazon.com/storagegateway/) is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage.

[AWS Transit Gateway](https://aws.amazon.com/transit-gateway/) is a tool that connects VPCs and on-premises networks through a central hub. This simplifies your network and puts an end to complex peering relationships. It acts as a cloud router - each new connection is only made once.

[Gateway Load Balancer (GWLB)](https://aws.amazon.com/elasticloadbalancing/gateway-load-balancer/) is a tool that makes it easy to deploy, scale, and manage your third-party virtual appliances. It gives you one gateway for distributing traffic across multiple virtual appliances, while scaling them up, or down, based on demand.

[AWS Chalice](https://aws.amazon.com/blogs/developer/deploying-aws-chalice-application-using-aws-cloud-development-kit/) is a Python Serverless Microframework for AWS and allows you to quickly create and deploy applications that use Amazon API Gateway and AWS Lambda.

[AWS ParallelCluster](https://aws.amazon.com/hpc/parallelcluster/) is an AWS supported Open Source cluster management tool to deploy and manage HPC clusters in the AWS cloud.

[AWS Copilot CLI](https://aws.amazon.com/containers/copilot/) is a tool for developers to build, release and operate production ready containerized applications on Amazon ECS and AWS Fargate.

[AWS Fargate](https://aws.amazon.com/fargate/) is a serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS).

[Amazon Chime](https://aws.amazon.com/chime/) is a communications service that lets you meet, chat, and place business calls inside and outside your organization, all using a single application.

[Amazon Virtual Private Cloud (Amazon VPC)](https://console.aws.amazon.com/vpc) is a service that lets you launch AWS resources in a logically isolated virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways.

[AWS Lightsail](https://aws.amazon.com/lightsail/) is an easy-to-use virtual private server (VPS) that offers you everything needed to build an application or website, plus a cost-effective, monthly plan.

[Amazon Relational Database Service (Amazon RDS)](https://console.aws.amazon.com/rds/home) is a tool that makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups.

[Amazon Aurora](https://console.aws.amazon.com/rds/home) is a MySQL and PostgreSQL-compatible relational database built for the cloud, that combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases.

[Amazon Athena](https://aws.amazon.com/athena/) is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run.

[Amazon CloudSearch](https://aws.amazon.com/cloudsearch/) is a managed service in the AWS Cloud that makes it simple and cost-effective to set up, manage, and scale a search solution for your website or application.

[Amazon Kinesis](https://aws.amazon.com/kinesis/) is a tool that makes it easy to collect, process, and analyze real-time, streaming data so you can get timely insights and react quickly to new information. Amazon Kinesis offers key capabilities to cost-effectively process streaming data at any scale, along with the flexibility to choose the tools that best suit the requirements of your application. With Amazon Kinesis, you can ingest real-time data such as video, audio, application logs, website clickstreams, and IoT telemetry data for machine learning, analytics, and other applications.

Amazon EMR is the industry-leading cloud big data platform for processing vast amounts of data using open source tools such as [Apache Spark](https://aws.amazon.com/emr/features/spark/), [Apache Hive](https://aws.amazon.com/emr/features/hive/), [Apache HBase](https://aws.amazon.com/emr/features/hbase/), [Apache Flink](https://aws.amazon.com/blogs/big-data/use-apache-flink-on-amazon-emr/),[Apache Hudi](https://aws.amazon.com/emr/features/hudi/), and [Presto](https://aws.amazon.com/emr/features/presto/).

[AWS RedShift](https://aws.amazon.com/redshift/) is a data warehouse tool that makes it as easy to gain new insights from all your data. With Redshift, you can easily query and combine exabytes of structured and semi-structured data across your data warehouse, operational database, and data lake using standard SQL. It lets you easily save the results of your queries back to your S3 data lake using open formats, like Apache Parquet, so that you can do additional analytics from other analytics services like Amazon EMR, Amazon Athena, and Amazon SageMaker.

[AWS Data Pipeline](https://aws.amazon.com/datapipeline/) is a web service that helps you reliably process and move data between different AWS compute and storage services, as well as on-premises data sources, at specified intervals. AWS Data Pipeline, let's you regularly access your data where it’s stored, transform and process it at scale, and efficiently transfer the results to AWS services such as Amazon S3, Amazon RDS, Amazon DynamoDB, and Amazon EMR.

[AWS Glue](https://aws.amazon.com/glue/) is a serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.

[AWS Lake Formation](https://aws.amazon.com/lake-formation/) is a service that makes it easy to set up a secure data lake in days. A data lake is a centralized, curated, and secured repository that stores all your data, both in its original form and prepared for analysis.

[Amazon Managed Blockchain](https://aws.amazon.com/managed-blockchain/) is a fully managed service that makes it easy to join public networks or create and manage scalable private networks using the popular open-source frameworks [Hyperledger Fabric](https://aws.amazon.com/blockchain/what-is-hyperledger-fabric/) and Ethereum.

[AWS Wavelength](https://aws.amazon.com/wavelength/) is an AWS Infrastructure offering optimized for mobile edge computing applications. Wavelength Zones are AWS infrastructure deployments that embed AWS compute and storage services within communications service providers’ (CSP) datacenters at the edge of the 5G network, so application traffic from 5G devices can reach application servers running in Wavelength Zones without leaving the telecommunications network.

[AWS Outposts](https://aws.amazon.com/outposts/) is a fully managed service that offers the same AWS infrastructure, AWS services, APIs, and tools to virtually any datacenter, co-location space, or on-premises facility for a truly consistent hybrid experience. AWS Outposts is ideal for workloads that require low latency access to on-premises systems, local data processing, data residency, and migration of applications with local system interdependencies.

[AWS Batch](https://aws.amazon.com/batch/) is atool that enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS. AWS Batch dynamically provisions the optimal quantity and type of compute resources (e.g., CPU or memory optimized instances) based on the volume and specific resource requirements of the batch jobs submitted. AWS Batch plans, schedules, and executes your batch computing workloads across the full range of AWS compute services and features, such as [AWS Fargate](https://aws.amazon.com/fargate/), [Amazon EC2](https://aws.amazon.com/ec2/) and [Spot Instances](https://aws.amazon.com/ec2/spot/).

[Amazon Forecast](https://aws.amazon.com/forecast/) is a fully managed service that uses machine learning to deliver highly accurate forecasts.

[AWS Snow Family](https://aws.amazon.com/snow/) is a highly-secure, portable devices to collect and process data at the edge, and migrate data into and out of AWS.

[Amazon Neptune](https://aws.amazon.com/neptune/) is a fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets. The core of Amazon Neptune is a purpose-built, high-performance graph database engine optimized for storing billions of relationships and querying the graph with milliseconds latency.

[Amazon Timestream](https://aws.amazon.com/timestream/) is a fast, scalable, and serverless time series database service for IoT and operational applications that makes it easy to store and analyze trillions of events per day up to 1,000 times faster and at as little as 1/10th the cost of relational databases.

[AWS IoT](https://aws.amazon.com/iot/) is a service that is built on a secure and proven cloud infrastructure, and scales to billions of devices and trillions of messages. It easily integrates with other AWS services, so you can build complete solutions.

[AWS IoT Core](https://aws.amazon.com/iot-core/) lets you connect IoT devices to the AWS cloud without the need to provision or manage servers. AWS IoT Core can support billions of devices and trillions of messages, and can process and route those messages to AWS endpoints and to other devices reliably and securely.

# Google Cloud Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/114321928-639d6080-9ad2-11eb-8297-5e6c10c1c792.png">
  <br />
</p>

**[Cloud Code for VS Code extension](https://cloud.google.com/code/docs/vscode/install)**

## Google Cloud Learning Resources

[Google Cloud Platform] is a public cloud platform that lets you build, deploy, and scale applications, websites, and services on the same infrastructure as Google.

[Google Cloud Courses and Training](https://cloud.google.com/training/)

[Architecting with Google Compute Engine](https://google.qwiklabs.com/courses/1421?utm_source=gcp_training&utm_medium=website&utm_campaign=cgc)

[Get started with Cloud Storage on Web with Firebase](https://firebase.google.com/docs/storage/web/start)

[Getting started with BigQuery](https://cloud.google.com/bigquery/docs/quickstarts)

[Machine Learning Crash Course with Google Cloud](https://developers.google.com/machine-learning/crash-course/)

[Architecting with Google Kubernetes Engine in Google Cloud](https://google.qwiklabs.com/courses/1232?utm_source=gcp_training&utm_medium=website&utm_campaign=cgc)

[Google Cloud Internet of Things (IoT)](https://developers.google.com/iot/)

[Google Cloud Certified Professional Cloud Security Engineer](https://cloud.google.com/certification/cloud-security-engineer)

[Google Cloud Courses on Coursera](https://www.coursera.org/googlecloud)

[Google Cloud Courses on Udemy](https://www.udemy.com/topic/google-cloud/)


## Google Cloud Tools

[Cloud SDK](https://cloud.google.com/sdk/) is a clietn tool used to to manage Google Cloud resources and applications with command-line tools and libraries. The Cloud SDK contains gcloud, gsutil, and bq command-line tools, which you can use to access [Compute Engine](https://cloud.google.com/compute), [Cloud Storage](https://cloud.google.com/storage), [BigQuery](https://cloud.google.com/bigquery), and more.

[Google Cloud Shell](https://cloud.google.com/shell/) is a free admin machine with browser-based command-line access for managing your infrastructure and applications on Google Cloud Platform.

[Cloud Code](https://cloud.google.com/code) is a client tool that writes, debugs, and run cloud-native applications, locally or in the cloud—quickly and easily. Extensions to IDEs such as Visual Studio Code and IntelliJ are provided to let you rapidly iterate, debug, and deploy code to Kubernetes.

[gcloud](https://cloud.google.com/sdk/gcloud/) is a CLI (command line interface) manages authentication, local configuration, developer workflow, interactions with Google Cloud APIs.

[gsutil](https://cloud.google.com/storage/docs/gsutil) is a Python application that lets you access Cloud Storage from the command line.

[Compute Engine](https://cloud.google.com/compute) is a secure and customizable compute service that lets you create and run virtual machines on Google’s infrastructure.

[App Engine](https://cloud.google.com/appengine/) is a client tool that lets you build and run applications on Google's infrastructure. It automatically scales to support sudden traffic spikes without provisioning, patching, or monitoring.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for deploying containerized applications.

[Cloud Storage](https://cloud.google.com/storage) is a Object storage for companies of all sizes. Where store any amount of data and retrieve it as often as you would like to.

[BigQuery](https://cloud.google.com/bigquery) is a serverless, highly scalable, and cost-effective multi-cloud data warehouse designed for business agility.

[Cloud Bigtable](https://cloud.google.com/bigtable/) is Google's fully managed NoSQL Big Data database service. It's the same database that powers many core Google services, including Search, Analytics, Maps, and Gmail.

[Cloud SQL](https://cloud.google.com/sql/) is a tool that makes it easy to set up, manage, and administer your Postgres databases on Google Cloud.

[Cloud Datastore](https://cloud.google.com/datastore/) is a schemaless database, which allows you to worry less about making changes to your underlying data structure as your application evolves.

[Cloud Pub/Sub](https://cloud.google.com/pubsub/) is a messaging middleware for traditional service integration or a simple communication medium for modern microservices.

[Cloud Dataflow](https://cloud.google.com/dataflow/) is a tool that brings streaming events to Google Cloud's AI Platform and TensorFlow Extended (TFX) to enable predictive analytics, fraud detection, real-time personalization, and other advanced analytics.

[Cloud Dataproc](https://cloud.google.com/dataproc/) is a fully managed and highly scalable service for running Apache Spark, Apache Flink, Presto, and 30+ open source tools and frameworks.

[Cloud Datalab](https://cloud.google.com/datalab/docs/) is a tool that provides a productive, interactive, and integrated tool to explore, visualize, analyze and transform data, bringing together the power of Python, SQL, JavaScript, and the Google Cloud Platform with services such as BigQuery and Storage.

[Cloud Vision API](https://cloud.google.com/vision/) is a library that offers powerful pre-trained machine learning models through REST and RPC APIs.

[Cloud Speech API](https://cloud.google.com/speech-to-text/) is a library that enables developers to convert audio to text by applying powerful neural network models. The API recognizes over 80 languages and variants, to support your global user base.

[Cloud Build](https://cloud.google.com/cloud-build) is a continuous build, test, and deploy software across all languages and in multiple environments—including VMs, serverless, Kubernetes, and Firebase.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[Jenkins on Google Cloud](https://cloud.google.com/jenkins) is a client tool that helps speed up, scale, and security from your Jenkins pipeline.

[Tekton on Google Cloud](https://cloud.google.com/tekton) is a client tool that standardizes CI/CD pipelines across languages, and tools on premises or in the cloud with a Kubernetes native open source framework.

[Artifact Registry](https://cloud.google.com/artifact-registry) is a client tool to manage container images and language packages such as Maven and npm all in one place, fully integrated with Google Cloud’s tooling and runtimes.

[Cloud Deployment Manager](https://cloud.google.com/deployment-manager) is a client that creates and manages cloud resources with simple templates. Specify all the resources needed for applications in a declarative format using yaml.

[Red Hat OpenShift on Google Cloud](https://cloud.google.com/solutions/partners/openshift-on-gcp) is a fully-managed and jointly supported Red Hat OpenShift offering that enables you to deploy stateful and stateless apps with nearly any language, framework, database, or service. It gives you a hosted environment entirely on Google Cloud. A hybrid environment where you maintain part of your workload on-premises or in a private hosting environment and migrate the rest to Google Cloud.

# Kubernetes
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/95383873-a884d800-08a0-11eb-8eaf-57af5b119f56.png">
  <br />
</p>

**[Working with Kubernetes in Visual Studio Code](https://code.visualstudio.com/docs/azure/kubernetes)**

<img src="https://user-images.githubusercontent.com/45159366/105645195-db9ea780-5e4e-11eb-8357-fb38b2f06d74.png">

**Building Highly-Availability(HA) Clusters with kubeadm. Source: [Kubernetes.io](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/high-availability/)**

## Kubernetes Learning Resources

[Kubernetes (K8s)](https://kubernetes.io/) is an open-source system for automating deployment, scaling, and management of containerized applications.

[Getting Kubernetes Certifications](https://training.linuxfoundation.org/certification/catalog/?_sft_technology=kubernetes)

[Getting started with Kubernetes on AWS](https://aws.amazon.com/kubernetes/)

[Kubernetes on Microsoft Azure](https://azure.microsoft.com/en-us/topic/what-is-kubernetes/)

[Intro to Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/kubernetes-dashboard)

[Azure Red Hat OpenShift ](https://azure.microsoft.com/en-us/services/openshift/)

[Getting started with Google Cloud](https://cloud.google.com/learn/what-is-kubernetes)

[Getting started with Kubernetes on Red Hat](https://www.redhat.com/en/topics/containers/what-is-kubernetes)

[Getting started with Kubernetes on IBM](https://www.ibm.com/cloud/learn/kubernetes)

[Red Hat OpenShift on IBM Cloud](https://www.ibm.com/cloud/openshift)

[Enable OpenShift Virtualization on Red Hat OpenShift](https://developers.redhat.com/blog/2020/08/28/enable-openshift-virtualization-on-red-hat-openshift/)

[YAML basics in Kubernetes](https://developer.ibm.com/technologies/containers/tutorials/yaml-basics-and-usage-in-kubernetes/)

[Elastic Cloud on Kubernetes](https://www.elastic.co/elastic-cloud-kubernetes)

[Docker and Kubernetes](https://www.docker.com/products/kubernetes)

[Running Apache Spark on Kubernetes](http://spark.apache.org/docs/latest/running-on-kubernetes.html)

[Kubernetes Across VMware vRealize Automation](https://blogs.vmware.com/management/2019/06/kubernetes-across-vmware-cloud-automation-services.html)

[VMware Tanzu Kubernetes Grid](https://tanzu.vmware.com/kubernetes-grid)

[All the Ways VMware Tanzu Works with AWS](https://tanzu.vmware.com/content/blog/all-the-ways-vmware-tanzutm-works-with-aws)

[VMware Tanzu Education](https://tanzu.vmware.com/education)

[Using Ansible in a Cloud-Native Kubernetes Environment](https://www.ansible.com/blog/how-useful-is-ansible-in-a-cloud-native-kubernetes-environment)

[Managing Kubernetes (K8s) objects with Ansible](https://docs.ansible.com/ansible/latest/collections/community/kubernetes/k8s_module.html)

[Setting up a Kubernetes cluster using Vagrant and Ansible](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)

[Running MongoDB with Kubernetes](https://www.mongodb.com/kubernetes)

[Kubernetes Fluentd](https://docs.fluentd.org/v/0.12/articles/kubernetes-fluentd)

[Understanding the new GitLab Kubernetes Agent](https://about.gitlab.com/blog/2020/09/22/introducing-the-gitlab-kubernetes-agent/)

[Intro Local Process with Kubernetes for Visual Studio 2019](https://devblogs.microsoft.com/visualstudio/introducing-local-process-with-kubernetes-for-visual-studio%E2%80%AF2019/)

[Kubernetes Contributors](https://www.kubernetes.dev/)

[KubeAcademy from VMware](https://kube.academy/)

[Kubernetes Tutorials from Pulumi](https://www.pulumi.com/docs/tutorials/kubernetes/)

[Kubernetes Playground by Katacoda](https://www.katacoda.com/courses/kubernetes/playground)

[Scalable Microservices with Kubernetes course from Udacity ](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615)

## Kubernetes Tools, Frameworks, and Projects

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io) is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for running containerized applications.

[Azure Kubernetes Service (AKS)](https://azure.microsoft.com/en-us/services/kubernetes-service/) is serverless Kubernetes, with a integrated continuous integration and continuous delivery (CI/CD) experience, and enterprise-grade security and governance. Unite your development and operations teams on a single platform to rapidly build, deliver, and scale applications with confidence.

[Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html) is a tool that runs Kubernetes control plane instances across multiple Availability Zones to ensure high availability.

[AWS Controllers for Kubernetes (ACK)](https://aws.amazon.com/blogs/containers/aws-controllers-for-kubernetes-ack/) is a new tool that lets you directly manage AWS services from Kubernetes. ACK makes it simple to build scalable and highly-available Kubernetes applications that utilize AWS services.

[Container Engine for Kubernetes (OKE)](https://www.oracle.com/cloud-native/container-engine-kubernetes/) is an Oracle-managed container orchestration service that can reduce the time and cost to build modern cloud native applications. Unlike most other vendors, Oracle Cloud Infrastructure provides Container Engine for Kubernetes as a free service that runs on higher-performance, lower-cost compute.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[Red Hat Openshift](https://www.openshift.com/) is a fully managed Kubernetes platform that provides a foundation for on-premises, hybrid, and multicloud deployments.

[OKD](https://okd.io/) is a community distribution of Kubernetes optimized for continuous application development and multi-tenant deployment. OKD adds developer and operations-centric tools on top of Kubernetes to enable rapid application development, easy deployment and scaling, and long-term lifecycle maintenance for small and large teams.

[Odo](https://odo.dev/) is a fast, iterative, and straightforward CLI tool for developers who write, build, and deploy applications on Kubernetes and OpenShift.

[Kata Operator](https://github.com/openshift/kata-operator) is an operator to perform lifecycle management (install/upgrade/uninstall) of [Kata Runtime](https://katacontainers.io/) on Openshift as well as Kubernetes cluster.

[Thanos](https://thanos.io/) is a set of components that can be composed into a highly available metric system with unlimited storage capacity, which can be added seamlessly on top of existing Prometheus deployments.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

[Rook](https://rook.io/) is a tool that turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management.

[VMware Tanzu](https://tanzu.vmware.com/tanzu) is a centralized management platform for consistently operating and securing your Kubernetes infrastructure and modern applications across multiple teams and private/public clouds.

[Kubespray](https://kubespray.io/) is a tool that combines Kubernetes and Ansible to easily install Kubernetes clusters that can be deployed on [AWS](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/aws.md), GCE, [Azure](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/azure.md), [OpenStack](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/openstack.md), [vSphere](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/vsphere.md), [Packet](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/packet.md) (bare metal), Oracle Cloud Infrastructure (Experimental), or Baremetal.

[KubeInit](https://github.com/kubeinit/kubeinit) provides Ansible playbooks and roles for the deployment and configuration of multiple Kubernetes distributions.

[Rancher](https://rancher.com/) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

[K3s](https://github.com/rancher/k3s) is a highly available, certified Kubernetes distribution designed for production workloads in unattended, resource-constrained, remote locations or inside IoT appliances.

[Helm](https://helm.sh/) is a Kubernetes Package Manager tool that makes it easier to install and manage Kubernetes applications.

[Knative](https://knative.dev/) is a Kubernetes-based platform to build, deploy, and manage modern serverless workloads. Knative takes care of the operational overhead details of networking, autoscaling (even to zero), and revision tracking.

[KubeFlow](https://www.kubeflow.org/) is a tool dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable.

[Etcd](https://etcd.io/) is a distributed key-value store that provides a reliable way to store data that needs to be accessed by a distributed system or cluster of machines. Etcd is used as the backend for service discovery and stores cluster state and configuration for Kubernetes.

[OpenEBS](https://openebs.io/) is a Kubernetes-based tool to create stateful applications using Container Attached Storage.

[Container Storage Interface (CSI)](https://www.architecting.it/blog/container-storage-interface/) is an API that lets container orchestration platforms like Kubernetes seamlessly communicate with stored data via a plug-in.

[MicroK8s](https://microk8s.io/) is a tool that delivers the full Kubernetes experience. In a Fully containerized deployment with compressed over-the-air updates for ultra-reliable operations. It is supported on Linux, Windows, and MacOS.

[Charmed Kubernetes](https://ubuntu.com/kubernetes/features) is a well integrated, turn-key, conformant Kubernetes platform, optimized for your multi-cloud environments developed by Canonical.

[Grafana Kubernetes App](https://grafana.com/grafana/plugins/grafana-kubernetes-app) is a toll that allows you to monitor your Kubernetes cluster's performance. It includes 4 dashboards, Cluster, Node, Pod/Container and Deployment. It allows for the automatic deployment of the required Prometheus exporters and a default scrape config to use with your in cluster Prometheus deployment.

[KubeEdge](https://kubeedge.io/en/) is an open source system for extending native containerized application orchestration capabilities to hosts at Edge.It is built upon kubernetes and provides fundamental infrastructure support for network, app. deployment and metadata synchronization between cloud and edge.

[Lens](https://k8slens.dev/)  is the most powerful IDE for people who need to deal with Kubernetes clusters on a daily basis. It has support for MacOS, Windows and Linux operating systems.

[kind](https://kind.sigs.k8s.io/) is a tool for running local Kubernetes clusters using Docker container “nodes”. It was primarily designed for testing Kubernetes itself, but may be used for local development or CI.

[Flux CD](https://fluxcd.io/) is a tool that automatically ensures that the state of your Kubernetes cluster matches the configuration you've supplied in Git. It uses an operator in the cluster to trigger deployments inside Kubernetes, which means that you don't need a separate continuous delivery tool.

[Platform9 Managed Kubernetes (PMK)](https://platform9.com/managed-kubernetes/) is a Kubernetes as a service that ensures fully automated Day-2 operations with 99.9% SLA on any environment, whether in data-centers, public clouds, or at the edge.

# Docker
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521410-2e32c900-954e-11eb-8311-065fa0099546.png">
  <br />
</p>

**[Get started with Docker using Visual Studio Code](https://docs.microsoft.com/en-us/visualstudio/docker/tutorials/docker-tutorial)**

**[Developing inside a Container with Visual Studio Code](https://code.visualstudio.com/docs/remote/containers)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521413-2ffc8c80-954e-11eb-9d19-b9c996bc524b.png">
  <br />
</p>

**Container Architecture. Source: [Containerd.io](https://containerd.io)**

## Docker Learning Resources

[Docker Training Program](https://www.docker.com/dockercon/training)

[Docker Certified Associate (DCA) certification](https://training.mirantis.com/dca-certification-exam/)

[Docker Documentation | Docker Documentation](https://docs.docker.com/)

[The Docker Workshop](https://courses.packtpub.com/courses/docker)

[Docker Courses on Udemy](https://www.udemy.com/topic/docker/)

[Docker Courses on Coursera](https://www.coursera.org/courses?query=docker)

[Docker Courses on edX](https://www.edx.org/learn/docker)

[Docker Courses on Linkedin Learning](https://www.linkedin.com/learning/topics/docker)

## Docker Tools

[Docker](https://www.docker.com/) is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly working in collaboration with cloud, Linux, and Windows vendors, including Microsoft.

[Docker Enterprise](https://www.mirantis.com/software/docker/docker-enterprise/) is a subscription including software, supported and certified container platform for CentOS, Red Hat Enterprise Linux (RHEL), Ubuntu, SUSE Linux Enterprise Server (SLES), Oracle Linux, and Windows Server 2016, as well as for cloud providers AWS and Azure. In [November 2019 Docker's Enterprise Platform business was acquired by Mirantis](https://www.mirantis.com/company/press-center/company-news/mirantis-acquires-docker-enterprise/).

[Docker Desktop](https://www.docker.com/products/docker-desktop) is an application for MacOS and Windows machines for the building and sharing of containerized applications and microservices. Docker Desktop delivers the speed, choice and security you need for designing and delivering containerized applications on your desktop. Docker Desktop includes Docker App, developer tools, Kubernetes and version synchronization to production Docker Engines.

[Docker Hub](https://hub.docker.com/) is the world's largest library and community for container images Browse over 100,000 container images from software vendors, open-source projects, and the community.

[Docker Compose](https://docs.docker.com/compose/) is a tool that was developed to help define and share multi-container applications. With Docker Compose, you can create a YAML file to define the services and with a single command, can spin everything up or tear it all down.

[Docker Swarm](https://docs.docker.com/engine/swarm/) is a Docker-native clustering system swarm is a simple tool which controls a cluster of Docker hosts and exposes it as a single "virtual" host.

[Dockerfile](https://docs.docker.com/engine/reference/builder/) is a text document that contains all the commands a user could call on the command line to assemble an image. Using docker build users can create an automated build that executes several command-line instructions in succession.

[Docker Containers](https://www.docker.com/resources/what-container) is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.

[Docker Engine](https://www.docker.com/products/container-runtime) is a container runtime that runs on various Linux (CentOS, Debian, Fedora, Oracle Linux, RHEL, SUSE, and Ubuntu) and Windows Server operating systems. Docker creates simple tooling and a universal packaging approach that bundles up all application dependencies inside a container which is then run on Docker Engine.

[Docker Images](https://docs.docker.com/engine/reference/commandline/images/) is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings. Images have intermediate layers that increase reusability, decrease disk usage, and speed up docker build by allowing each step to be cached. These intermediate layers are not shown by default. The SIZE is the cumulative space taken up by the image and all its parent images.

[Docker Network](https://docs.docker.com/engine/reference/commandline/network/) is a that displays detailed information on one or more networks.

[Docker Daemon](https://docs.docker.com/config/daemon/) is a service started by a system utility, not manually by a user. This makes it easier to automatically start Docker when the machine reboots. The command to start Docker depends on your operating system. Currently, it only runs on Linux because it depends on a number of Linux kernel features, but there are a few ways to run Docker on MacOS and Windows as well by configuring the operating system utilities.

[Docker Storage](https://docs.docker.com/storage/storagedriver/select-storage-driver/) is a driver controls how images and containers are stored and managed on your Docker host.

[Kitematic](https://kitematic.com/) is a simple application for managing Docker containers on Mac, Linux and Windows letting you control your app containers from a graphical user interface (GUI).

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io) is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows.

# Ansible
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113448802-62bd4e00-93b1-11eb-9114-419e758af23b.png">
  <br />
</p>

**[Ansible VS Code Extension](https://marketplace.visualstudio.com/items?itemName=tomaciazek.ansible)**

## Ansible Learning Resources

[Ansible](https://www.ansible.com/) is a simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs. It uses a very simple language (YAML, in the form of Ansible Playbooks) that allows you to describe your automation jobs in a way that approaches plain English. Anisble works on Linux (Red Hat EnterPrise Linux(RHEL) and Ubuntu) and Microsoft Windows.

[Red Hat Training for Ansible](https://www.ansible.com/products/training-certification)

[Top Ansible Courses Online from Udemy](https://www.udemy.com/topic/ansible/)

[Introduction to Ansible: The Fundamentals on Coursera](https://www.coursera.org/projects/ansible-fundamentals)

[Learning Ansible Fundamentals on Pluralsight](https://www.pluralsight.com/courses/ansible-fundamentals)

[Ansible Documentation](https://docs.ansible.com/ansible/latest/index.html)

[Anislbe Galaxy User Guide](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html)

[Anisble Use Cases](https://www.ansible.com/use-cases?hsLang=en-us)

[Anisble Integrations](https://www.ansible.com/integrations?hsLang=en-us)

[Working with playbooks](https://docs.ansible.com/ansible/latest/user_guide/playbooks.html)

[Getting Started: Writing Your First Playbook - Ansible](https://www.ansible.com/blog/getting-started-writing-your-first-playbook)

[Working With Modules in Ansible](https://docs.ansible.com/ansible/latest/user_guide/modules.html)

[Ansible Best Practices: Roles & Modules](https://www.ansible.com/resources/webinars-training/ansible-best-practices-roles-modules)

[Working with command line tools for Ansible](https://docs.ansible.com/ansible/latest/user_guide/command_line_tools.html)

[Encrypting content with Ansible Vault](https://docs.ansible.com/ansible/latest/user_guide/vault.html)

[Using vault in playbooks with Ansible ](https://docs.ansible.com/ansible/latest/user_guide/playbooks_vault.html)

[How to Use Ansible: An Ansible Cheat Sheet Guide from DigitalOcean](https://www.digitalocean.com/community/cheatsheets/how-to-use-ansible-cheat-sheet-guide)


## Ansible DevOps Tools Integration

[Ansible cmdb](https://github.com/fboender/ansible-cmdb) is a tool that takes the output of Ansible’s fact gathering and converts it into a static HTML overview page containing system configuration information.

[Ansible Inventory Grapher](https://github.com/willthames/ansible-inventory-grapher) visually displays inventory inheritance hierarchies and at what level a variable is defined in inventory.

[Ansible Playbook Grapher](https://github.com/haidaraM/ansible-playbook-grapher) is a  command line tool to create a graph representing your Ansible playbook tasks and roles.

[Ansible Shell](https://github.com/dominis/ansible-shell) is an interactive shell for Ansible with built-in tab completion for all the modules.

[Ansible Silo](https://github.com/groupon/ansible-silo) is a self-contained Ansible environment by [Docker](https://www.docker.com/).

[Ansigenome](https://github.com/nickjj/ansigenome) is a command line tool designed to help you manage your Ansible roles.

[ARA](https://github.com/openstack/ara) is a records Ansible playbook runs and makes the recorded data available and intuitive for users and systems by integrating with Ansible as a callback plugin.

[Red Hat OpenShift](https://www.openshift.com/) is focused on security at every level of the container stack and throughout the application lifecycle. It includes long-term, enterprise support from one of the leading Kubernetes contributors and open source software companies.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

[GitHub](https://github.com/) provides hosting for software development version control using Git. It offers all of the distributed version control and source code management functionality of Git as well as adding its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code.

[GitHub Actions](https://docs.github.com/en/actions) will automate, customize, and execute your software development workflows right in your repository with GitHub Actions. You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.[GitHub Actions for Azure](https://docs.microsoft.com/en-us/azure/developer/github/github-actions) you can create workflows that you can set up in your repository to build, test, package, release and deploy to Azure.

# Terraform
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121819653-245ecd80-cc43-11eb-950a-cb4db09481b6.png">
  <br />
</p>

**[HashiCorp Terraform Visual Studio Code (VS Code) extension](https://marketplace.visualstudio.com/items?itemName=hashicorp.terraform)**

## Terraform Learning Resources

[Terraform](https://www.terraform.io/) is an open-source infrastructure as code software tool created by HashiCorp.It enables users to define and provision a datacenter infrastructure using a high-level configuration language known as [Hashicorp Configuration Language (HCL)](https://github.com/hashicorp/hcl), or optionally JSON.

[Terraform Documentation](https://www.terraform.io/docs/index.html)

[Terraform API Docs](https://www.terraform.io/docs/cloud/api/index.html)

[Terraform Providers](https://registry.terraform.io/browse/providers)

[Terraform Modules](https://registry.terraform.io/browse/modules)

[HashiCorp GitHub](https://github.com/hashicorp)

[HashiCorp Discuss Forum](https://discuss.hashicorp.com/c/terraform-core)

[HashiCorp's Learn Platform](https://learn.hashicorp.com/terraform)

[HashiCorp Certified: Terraform Associate](https://www.hashicorp.com/certification/#hashicorp-certified-terraform-associate)

[HashiCorp Certifications](https://www.hashicorp.com/certification)

[What is Terraform? | IBM](https://www.ibm.com/cloud/learn/terraform)

[Terraform on Azure](https://docs.microsoft.com/en-us/azure/developer/terraform/)

[Automate Terraform with GitHub Actions](https://learn.hashicorp.com/tutorials/terraform/github-actions)

[Using Terraform to Manage AWS Programmable Infrastructures](https://aws.amazon.com/blogs/apn/using-terraform-to-manage-aws-programmable-infrastructures/)

[Using Terraform with Google Cloud](https://cloud.google.com/docs/terraform)

[Top Terraform Courses on Udemy](https://www.udemy.com/topic/terraform/)

[Complete Terraform Course - Beginner to Advanced on Udemy](https://www.udemy.com/course/terraform-beginner-to-advanced/)

[Terraform Course: Fundamentals on Pluralsight](https://www.pluralsight.com/courses/terraform-getting-started)

[Terraform Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/terraform)

## Terraform Tools and Services

[Terraform Enterprise](https://www.hashicorp.com/products/terraform/editions/enterprise) is our self-hosted distribution of Terraform Cloud. It offers enterprises a private instance of the Terraform Cloud application, with no resource limits and with additional enterprise-grade architectural features like audit logging and SAML single sign-on.

[Terraform CLI](https://www.terraform.io/docs/cli/index.html) is a command-line tool used for working with Terraform's CLI-based workflows; this includes people who use Terraform CLI by itself, as well as those who use Terraform CLI in conjunction with Terraform Cloud or Terraform Enterprise.

[Terraform Registry](https://registry.terraform.io/) is a tool that makes it easy to use any provider or module. To use a provider or module from this registry, just add it to your configuration; when you run `terraform init`, Terraform will automatically download everything it needs.

[Terraform Cloud](https://www.terraform.io/cloud) is HashiCorp’s managed service offering that eliminates the need for unnecessary tooling and documentation to use Terraform in production.

[Hashicorp Configuration Language (HCL)](https://github.com/hashicorp/hcl) is a toolkit for creating structured configuration languages that are both human- and machine-friendly, for use with command-line tools. Although intended to be generally useful, it is primarily targeted towards devops tools and servers.

[CDK (Cloud Development Kit) for Terraform](https://github.com/hashicorp/terraform-cdk) is a toolkit that allows developers to use familiar programming languages to define cloud infrastructure and provision it through HashiCorp Terraform.

[Terraform-exec](https://github.com/hashicorp/terraform-exec) is a  Go module for constructing and running Terraform CLI commands. Structured return values use the data types defined in [terraform-json](https://github.com/hashicorp/terraform-json).

[TFSEC](https://github.com/tfsec/tfsec) is a security scanner for your Terraform code.

[Qovery Engine](https://github.com/Qovery/engine) is an open-source abstraction layer library that turns easy apps deployment on AWS, GCP, Azure, and other Cloud providers in just a few minutes. The Qovery Engine is written in Rust and takes advantage of Terraform, Helm, Kubectl, and Docker to manage resources.

# Windows Subsystem for Linux (WSL)

[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/82762656-18de0180-9db7-11ea-9676-ee6fcae615a1.png">
</p>

<img src="https://user-images.githubusercontent.com/45159366/107585931-e6c63700-6bb3-11eb-8f25-f07f8ff05688.png">


## WSL Learning Resources

[WSL 2 Linux Kernel on GitHub](https://github.com/microsoft/WSL2-Linux-Kernel) is the source for the Linux kernel used in Windows Subsystem for Linux 2 (WSL2).

[WSLConf](https://www.youtube.com/playlist?list=PLwFSk464RMxnZkvZ1HKrlNyj-s6Zq4fWe) is a community-initiated event on all things Windows Subsystem for Linux and WSL-related.

[What is the Windows Subsystem for Linux?](https://docs.microsoft.com/en-us/windows/wsl/about)

[Pro Windows Subsystem for Linux (WSL): Powerful Tools and Practices for Cross-Platform Development and Collaboration Book](https://www.amazon.com/Windows-Subsystem-Linux-Cross-Platform-Collaboration/dp/1484268725/ref=sr_1_1?dchild=1&keywords=Pro+Windows+Subsystem+for+Linux+%28WSL%29&qid=1614379171&s=digital-text&sr=1-1-catcorr)

[Windows Subsystem for Linux 2 (WSL 2) Tips, Tricks, and Techniques Book](https://www.amazon.com/Windows-Subsystem-Linux-Tricks-Techniques-ebook/dp/B08K98C7DB/ref=sr_1_1?dchild=1&keywords=WSL+book&qid=1614379053&s=digital-text&sr=1-1)

[Comparing WSL 2 and WSL 1 ](https://docs.microsoft.com/en-us/windows/wsl/compare-versions)

[GPU accelerated machine learning training in the Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/tutorials/gpu-compute)

[CUDA on Windows Subsystem for Linux(WSL) 2](https://developer.nvidia.com/blog/announcing-cuda-on-windows-subsystem-for-linux-2/)

[Developing in Windows Subsystem for Linux (WSL)](https://code.visualstudio.com/docs/remote/wsl)

[Using WSL 2 with Visual Studio Code](https://code.visualstudio.com/blogs/2019/09/03/wsl2)

[WSLG: X11 and Wayland Applications in WSL](https://linuxplumbersconf.org/event/9/contributions/611/attachments/702/1298/XDC2020_-_X11_and_Wayland_applications_in_WSL.pdf)

[How to run Podman on Windows with WSL 2](https://www.redhat.com/sysadmin/podman-windows-wsl2)

[Create a development container in Visual Studio Code](https://code.visualstudio.com/docs/remote/create-dev-container)

[Getting started with MySQL, MongoDB, PostgreSQL, SQLite, Microsoft SQL Server, or Redis to set up a database on WSL](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-database)

[Setting up SAP HANA, express edition into WSL 2 (Windows Subsystem for Linux)](https://blogs.sap.com/2020/09/30/installing-sap-hana-express-edition-into-wsl2-windows-subsystem-for-linux/)

[Set up your Node.js development environment with WSL 2](https://docs.microsoft.com/en-us/windows/nodejs/setup-on-wsl2)

[Getting started mounting a Linux disk in WSL 2](https://docs.microsoft.com/en-us/windows/nodejs/setup-on-wsl2)

[Using Fedora with Microsoft's WSL 2](https://fedoramagazine.org/wsl-fedora-33/)

## WSL Tools & Projects

[wslu](https://github.com/wslutilities/wslu) is a collection of utilities for Windows 10 Linux Subsystem, such as retrieving Windows 10 environment variables or creating your favorite Linux GUI application shortcuts on Windows 10 Desktop.

[Ubuntu on WSL](https://wiki.ubuntu.com/WSL) is a wiki guide on getting started with the latest version of Ubuntu installed and setup on WSL for Windows 10.

[Ubuntu on Windows Community Preview](https://www.microsoft.com/en-us/p/ubuntu-on-windows-community-preview/9p9q5zh1hrr0) is a special build of Ubuntu for WSL as a sandbox for testing new features and getting community feedback. This build is intended for early adopters in the WSL community.

[Ubuntu Pro for Azure](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/canonical.0001-com-ubuntu-pro-focal?tab=Overview) is a premium image designed by Canonical optimized for production environments running on Azure. It includes security and compliance services, enabled by default, in a form suitable for small to large-scale Linux enterprise operations — with no contract needed.

[Azure CLI](https://docs.microsoft.com/en-us/cli/azure/?view=azure-cli-latest) is a set of commands used to create and manage Azure resources. The Azure CLI is available across Azure services and is designed to get you working quickly with Azure, with an emphasis on automation.

[Visual Studio Code Remote - WSL extension](https://code.visualstudio.com/docs/remote/wsl) lets you use the Windows Subsystem for Linux (WSL) as your full-time development environment right from VS Code. You can develop in a Linux-based environment, use Linux-specific toolchains and utilities, and run and debug your Linux-based applications all from the comfort of Windows. The extension runs commands and other extensions directly in WSL so you can edit files located in WSL or the mounted Windows filesystem (for example /mnt/c) without worrying about pathing issues, binary compatibility, or other cross-OS challenges.

[Visual Studio Code Remote Development and GitHub Codespaces](https://github.com/Microsoft/vscode-dev-containers) is a  repository of development container definitions for the VS Code Remote - Containers extension and GitHub Codespaces. A development container is a running [Docker](https://www.docker.com/) container with a well-defined tool/runtime stack and its prerequisites. The [VS Code Remote Containers](https://aka.ms/vscode-remote/download/containers) extension allows you to clone a repository or open any folder mounted into (or already inside) a dev container and take advantage of VS Code's full development feature set. [GitHub Codespaces](https://github.com/features/codespaces) both use this same concept to quickly create customized, cloud-based development environments accessible from VS Code or the web.

[Windows Terminal](https://github.com/microsoft/terminal) is a new, modern, feature-rich, productive terminal application for command-line users. It includes many of the features most frequently requested by the Windows command-line community including support for tabs, rich text, globalization, configurability, theming & styling, and more.

[PowerShell Core](https://github.com/PowerShell/PowerShell) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models. It includes a command-line shell, an associated scripting language and a framework for processing cmdlets.

[Docker Desktop WSL 2 backend](https://docs.docker.com/docker-for-windows/wsl/) creates an  architectural change that gvies a full Linux kernel built by Microsoft, allowing Linux containers to run natively without emulation. With Docker Desktop running on WSL 2, users can leverage Linux workspaces and avoid having to maintain both Linux and Windows build scripts. In addition, WSL 2 provides improvements to file system sharing, boot time, and allows access to some cool new features for Docker Desktop users.

[Dxgkrnl](https://devblogs.microsoft.com/directx/directx-heart-linux/) is a brand-new kernel driver for Linux that exposes the /dev/dxg device to user mode Linux. /dev/dxg exposes a set of IOCTL that closely mimic the native WDDM D3DKMT kernel service layer on Windows. Dxgkrnl inside of the Linux kernel connects over the VM Bus to its big brother on the Windows host and uses this VM bus connection to communicate with the physical GPU.

[Ansible-WSL](https://github.com/Wintus/Ansible-WSL) is an open source program that makes it easier to provision your Windows from inside of WSL by Ansible.

[WSL-DistroLauncher](https://github.com/Microsoft/WSL-DistroLauncher) is a sample/reference launcher app for WSL distro Microsoft Store packages.

[Pengwin](https://github.com/WhitewaterFoundry/Pengwin) is a Linux distro optimized for WSL based on Debian.

[Pengwin Enterprise](https://github.com/WhitewaterFoundry/Pengwin-Enterprise) is an enterprise Linux solution for Windows Subsystem for Linux (WSL) that is compatible with mainstream enterprise Linux distributions.


## Setting up WSL Linux Distributions

**Requirements**

Before you install any of the Linux Distributions make sure to install/enable the Windows Subsystem for Linux on your Windows 10 machine. Following the instructions below:

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110054829-ad936980-7d10-11eb-80bd-bc5e96d31d27.png">
<br />
Installing Windows Subsystem Linux
</p>

**OR**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/109565559-7fefbb80-7a97-11eb-8502-4d8f2eeb4842.png">
 </p>

**For more technical users you run this command in Powershell:**

```sh
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```

[Ubuntu 20.04 LTS](https://www.microsoft.com/en-us/p/ubuntu-2004-lts/9n6svws3rx71?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563752-0eaf0900-7a95-11eb-9fd7-9be123b57cc1.png">
</p>


[Debian](https://www.microsoft.com/en-us/p/debian/9msvkqc78pk6?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563781-14a4ea00-7a95-11eb-8008-61867e38cf1e.png">
</p>

[Fedora 33 fo WSL](https://fedoramagazine.org/wsl-fedora-33/)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563789-15d61700-7a95-11eb-9c99-c1e68ead8388.png">
</p>

[SUSE Linux Enterprise Server 15 SP1](https://www.microsoft.com/en-us/p/suse-linux-enterprise-server-15-sp1/9pn498vpmf3z?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563809-1bcbf800-7a95-11eb-8be7-e94b2feb74a7.png">
</p>


[openSUSE Leap 15.2](https://www.microsoft.com/en-us/p/opensuse-leap-152/9mzd0n9z4m4h?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563802-1a9acb00-7a95-11eb-9c6a-14bbcde765dd.png">
</p>

[Kali Linux](https://www.microsoft.com/en-us/p/kali-linux/9pkr34tncv07?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563822-1ec6e880-7a95-11eb-8d4b-a051178da3e2.png">
</p>

[Pengwin](https://www.microsoft.com/en-us/p/pengwin/9nv1gv1pxz6p?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563833-225a6f80-7a95-11eb-93e8-f40799469bcc.png">
</p>


[Fedora Remix for WSL](https://www.microsoft.com/en-us/p/fedora-remix-for-wsl/9n6gdm4k2hnc?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563839-238b9c80-7a95-11eb-8a41-fc9775c810bb.png">
</p>


[GWSL](https://www.microsoft.com/en-us/p/gwsl/9nl6kd1h33v3?activetab=pivot:overviewtab) is an XServer that lets you easily run graphical Linux apps on Windows 10.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563870-2e463180-7a95-11eb-93b1-77c1ff0ef39d.png">
</p>

# GraphQL Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/120384173-aa415700-c2da-11eb-8a5c-9cea16d08686.png">
  <br />
</p>

**[GraphQL for VSCode](https://marketplace.visualstudio.com/items?itemName=GraphQL.vscode-graphql)**

## GraphQL Learning Resources

[GraphQL](https://graphql.org/) is a query language for APIs and a runtime for fulfilling those queries with your existing data. GraphQL provides a complete and understandable description of the data in your API, gives clients the power to ask for exactly what they need and nothing more, makes it easier to evolve APIs over time, and enables powerful developer tools.

[Learning GraphQL](https://graphql.org/learn/)

[GraphQL Community](https://graphql.org/community/)

[GraphQL Landscape](https://landscape.graphql.org)

[GraphQL Foundation](https://graphql.org/foundation/)

[GitHub GraphQL API ](https://docs.github.com/en/graphql)

[GraphQL Supported Programming Languages](https://graphql.org/code/#language-support)

[GraphQL Code Tools](https://graphql.org/code/#generic-tools)

[GraphQL Services](https://graphql.org/code/#services)

[Top GraphQL Courses on Udemy](https://www.udemy.com/topic/graphql/)

[Learning GraphQL Online Classes on LinkedIn Learning](https://www.linkedin.com/learning/learning-graphql)

[GraphQL Tutorials on Dgraph](https://dgraph.io/learn/)

[GraphQL Training Courses on NobleProg](https://www.nobleprog.com/graphql-training)

[GraphQL: The Big Picture Course on Pluralsight](https://www.pluralsight.com/courses/graphql-big-picture)

[Building Scalable APIs with GraphQL on Pluralsight](https://www.pluralsight.com/courses/graphql-scalable-apis)

[Consuming a GraphQL API with Apollo Client and React on Pluralsight](https://www.pluralsight.com/courses/consuming-graphql-api-with-apollo-client-react)

[Exploring GraphQL: A Query Language for APIs on edX](https://www.edx.org/course/exploring-graphql-a-query-language-for-apis)


## GraphQL Tool, Libraries, and Frameworks

[GraphQL CLI](https://github.com/Urigo/graphql-cli) is a command line tool for common GraphQL development workflows.

[GraphQL Tools](https://github.com/ardatan/graphql-tools) is a set of utils for faster development of GraphQL tools (Schema and documents loading, Schema merging and more).

[GraphQL Inspector](https://github.com/kamilkisiela/graphql-inspector) is a tool that compares schemas, validate documents, find breaking changes, find similar types, schema coverage, and more.

[GraphQL Mesh](https://github.com/Urigo/graphql-mesh) is a tool that allows you to use GraphQL query language to access data in remote APIs that don't run GraphQL (and also ones that do run GraphQL). It can be used as a gateway to other services, or run as a local GraphQL schema that aggregates data from remote APIs.

[GraphQL Scalars](https://github.com/Urigo/graphql-scalars) is a library of custom GraphQL scalar types for creating precise, type-safe GraphQL schemas.

[GraphQL Modules](https://github.com/Urigo/graphql-modules) is a lets you separate your backend implementation to small, reusable, easy-to-implement and easy-to-test pieces.

[GraphQL Config](https://github.com/kamilkisiela/graphql-config) is a tool that deos one configuration for all your GraphQL tools (supported by most tools, editors & IDEs).

[GraphQLShield](https://github.com/maticzav/graphql-shield) is a tool that helps you create a permission layer for your application. Using an intuitive rule-API, you'll gain the power of the shield engine on every request and reduce the load time of every request with smart caching. This way you can make sure your application will remain quick, and no internal data will be exposed.

[GraphQL Request](https://github.com/prisma-labs/graphql-request) is a simple and flexible JavaScript GraphQL client that works in all JavaScript environments (the browser, Node.js, and React Native) - basically a lightweight wrapper around fetch.

[Gatsby](https://www.gatsbyjs.com/) is a free and open source framework based on React that helps developers build blazing fast websites and apps.

[Dgraph](https://dgraph.io/) is a native GraphQL graph database that is built to be distributed. This makes it highly scalable, performant, and blazingly fast - even for complex queries over terabytes of data.

[GraphQL.js](https://www.npmjs.com/package/graphql) is a general-purpose library and can be used both in a Node server and in the browser. As an example, the GraphiQL tool is built with GraphQL.js. So building a project using GraphQL.js with webpack or rollup should just work and only include the portions of the library you use.

[urql](https://github.com/FormidableLabs/urql) is a GraphQL client that exposes a set of helpers for several frameworks. It's built to be highly customisable and versatile so you can take it from getting started with your first GraphQL project all the way to building complex apps and experimenting with GraphQL clients.

[React Starter Kit](https://www.reactstarterkit.com/) is an isomorphic web app boilerplate for web development built on top of [Node.js](https://nodejs.org/), [Express](http://expressjs.com/), [GraphQL](http://graphql.org/) and [React](https://facebook.github.io/react/), containing modern web development tools such as [Webpack](https://webpack.github.io/), [Babel](https://babeljs.io/) and [Browsersync](https://www.browsersync.io/). Helping you to stay productive following the best practices.

[React Hook Form](https://react-hook-form.com/) is a performant, flexible and extensible forms with easy to use validation(Web + React Native).

[Apollo Client](https://apollographql.com/client) is a fully-featured caching GraphQL client with integrations for React, Angular, and more. It allows you to easily build UI components that fetch data via GraphQL.

[Relay](https://github.com/facebook/relay) is Facebook's framework for building React applications that talk to a GraphQL backend.

[Strapi](https://github.com/strapi/strapi) is an open source Node.js Headless CMS to easily build customisable APIs.

[Prettier](https://github.com/prettier/prettier) is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

[Hasura GraphQL Engine](https://github.com/hasura/graphql-engine) is a blazing-fast GraphQL server that gives you instant, realtime GraphQL APIs over Postgres, with [webhook triggers](https://github.com/hasura/graphql-engine/blob/master/event-triggers.md) on database events, and [remote schemas](https://github.com/hasura/graphql-engine/blob/master/remote-schemas.md) for business logic.

[Nest](https://nestjs.com/) is a framework for building efficient, scalable [Node.js](http://nodejs.org/) server-side applications. It uses modern JavaScript, is built with TypeScript (preserves compatibility with pure JavaScript) and combines elements of OOP (Object Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming).

[PostGraphile](https://github.com/graphile/postgraphile) is a tool that builds a powerful, extensible and performant GraphQL API from a PostgreSQL schema in seconds; saving you weeks if not months of development time.

[Lokka](https://github.com/kadirahq/lokka) simple JavaScript GraphQL client that works in all JavaScript environments (the browser, Node.js, and React Native).

# .NET Development

[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719689-0d1e0400-fb39-11ea-82e5-331a8ff8060d.png">

</p>

## .NET Learning Resources

[.NET](https://dotnet.microsoft.com/learn/dotnet/what-is-dotnet) is a developer platform with tools and libraries for building any type of app, including web, mobile, desktop, games, IoT, cloud, and microservices.

[.NET documentation](https://docs.microsoft.com/en-us/dotnet/fundamentals/)

[Getting started with .NET](https://docs.microsoft.com/en-us/dotnet/standard/get-started)

[.NET Application Architecture Guide](https://dotnet.microsoft.com/learn/dotnet/architecture-guides)

[Intro .NET Guide by JetBrains ](https://blog.jetbrains.com/dotnet/2020/07/09/introducing-the-net-guide-tutorials-and-tips-tricks-for-net-rider-and-resharper/)

[C# documentation](https://docs.microsoft.com/en-us/dotnet/csharp/) write any application using the C# programming language on the .NET platform.

## .NET Tools

[.NET Core](https://docs.microsoft.com/en-us/dotnet/core/introduction) is a cross-platform .NET implementation for websites, servers, and console apps on Windows, Linux, and macOS.The .NET Framework supports websites, services, desktop apps, and more on Windows. Xamarin/Mono is a .NET implementation for running apps on all the major mobile operating systems.

[.NET runtime](https://github.com/dotnet/runtime) is a collection of libraries and shared host (dotnet) installers for all supported platforms, as well as the sources to .NET runtime and libraries.

[ASP.NET Core](https://asp.net/) is a cross-platform .NET framework for building modern cloud-based web applications on Windows, Mac, or Linux.

[Mono](https://www.mono-project.com/) is a software platform designed to allow developers to easily create cross platform applications. It is an open source implementation of Microsoft's .NET Framework based on the ECMA standards for C# and the Common Language Runtime.

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Rider](https://www.jetbrains.com/rider/) is a fast and powerful, cross-platform .NET IDE devloped by JetBrains to develop .NET, ASP.NET, .NET Core, Xamarin; or Unity applications for Windows, Mac, Linux.

[Resharper](https://www.jetbrains.com/resharper/) is a [Visual Studio](https://visualstudio.microsoft.com/) Extension for .NET Developers that has On-the-fly code quality analysis for C#, VB.NET, XAML, ASP.NET, ASP.NET MVC, JavaScript, TypeScript, CSS, HTML, and XML. Letting you know right away if your code needs to be improved.

[dotTrace](https://www.jetbrains.com/profiler/) is an .NET performance Profiler developed by Jet Brains. It helps users locate performance bottlenecks in a variety of .NET applications: desktop applications, .NET Core, ASP.NET, ASP.NET Core applications hosted on IIS or IIS Express web servers, Silverlight, WCF services, Windows services, Universal Windows Platform applications, and unit tests.

[dotMemory](https://www.jetbrains.com/dotmemory/) is an .NET memory Profiler developed by Jet Brains. It allows the user to analyze memory usage in a variety of .NET and .NET Core applications: desktop applications, Windows services, ASP.NET web applications, IIS, IIS Express, arbitrary .NET processes, and more.

[dotCover](https://www.jetbrains.com/dotcover/) is an .NET unit test runner and code coverage tool developed by Jet Brains. It helps the user figure out on-the-fly which unit tests are affected by your latest code changes, and automatically re-runs the affected tests for you. The continuous testing mode can be switched on for any unit test session.

[Avalonia](https://avaloniaui.net/) is a cross-platform XAML-based UI framework providing a flexible styling system and supporting a wide range of Operating Systems such as Windows via .NET Framework and .NET Core, Linux via Xorg, macOS.

[Polly](https://github.com/App-vNext/Polly) is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner.

[IdentityServer](https://identityserver.io/) is a free, open source [OpenID Connect](https://openid.net/connect/) and [OAuth 2.0](https://tools.ietf.org/html/rfc6749) framework for ASP.NET Core. IdentityServer4 incorporates all the protocol implementations and extensibility points needed to integrate token-based authentication, single-sign-on and API access control in your applications.

[ILSpy](https://github.com/icsharpcode/ILSpy) is the open-source .NET assembly browser and decompiler.

[Hangfire](https://www.hangfire.io/) is an easy way to perform background job processing in your .NET and .NET Core applications with no Windows Service or Task Scheduler required.

[React Native Windows](https://microsoft.github.io/react-native-windows/) is a ramework for building native Windows apps with React. [React Native](https://reactnative.dev/) is a framework developed by Facebook that enables you to build world-class application experiences on native platforms using a consistent developer experience based on JavaScript and React.

[ReactiveUI](https://reactiveui.net/) is a composable, cross-platform model-view-viewmodel framework for all .NET platforms that is inspired by functional reactive programming, which is a paradigm that allows you to abstract mutable state away from your user interfaces and express the idea around a feature in one readable place and improve the testability of your application.

[Refit](https://reactiveui.github.io/refit/) is the automatic type-safe REST library for .NET Core, Xamarin and .NET.It's heavily inspired by Square's Retrofit library, Refit turns your REST API into a live interface.

[MAUI](https://github.com/dotnet/maui) is the .NET Multi-platform App UI, a framework for building native device applications spanning mobile, tablet, and desktop.

[Quasar](https://github.com/quasar/Quasar) is a fast and light-weight remote administration tool coded in C#. The usage ranges from user support through day-to-day administrative work to employee monitoring. Providing high stability and an easy-to-use user interface, Quasar is the perfect remote administration solution for you.

# C# Development

[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306457-d6c0fa00-ff27-11ea-85dc-83dbb8f3e3e6.png">
  <br />

</p>

**[Start building with C# on Azure](https://docs.microsoft.com/en-us/azure/search/tutorial-csharp-create-first-app)**

**[C# Documentation](https://docs.microsoft.com/en-us/dotnet/csharp/)**

## C# Learning  Resources

[C#](https://docs.microsoft.com/en-us/dotnet/csharp/) is a modern and object-oriented programming language developed by Microsoft to write any application using the C# programming language on the .NET platform.

[Taking your first steps with C#](https://docs.microsoft.com/en-us/learn/paths/csharp-first-steps/)

[Learning C#](https://dotnet.microsoft.com/learn/csharp)

[C# development with Visual Studio](https://docs.microsoft.com/en-us/visualstudio/get-started/csharp/)

[C# programming with Visual Studio Code](https://code.visualstudio.com/Docs/languages/csharp)

[Working with data in C#](https://docs.microsoft.com/en-us/learn/paths/csharp-data/)

[C# Tutorial by W3Schools](https://www.w3schools.com/cs/)

[Windows Forms for .NET 5 and .NET Core 3.1](https://docs.microsoft.com/en-us/dotnet/desktop/winforms/?view=netdesktop-5.0)

[Xamarin documentation](https://docs.microsoft.com/en-us/xamarin/)

[Advanced Topics in C# by Udemy](https://www.udemy.com/course/advanced-topics-csharp/)

[The complete C# tutorial](https://csharp.net-tutorials.com/)

[Unity C# Survival Guide](https://learn.unity.com/course/unity-c-survival-guide)

[RabbitMQ .NET/C# Client API](https://www.rabbitmq.com/dotnet-api-guide.html)

## C# Tools

[Mono](https://www.mono-project.com/) is a software platform designed to allow developers to easily create cross platform applications. It is an open source implementation of Microsoft's .NET Framework based on the ECMA standards for C# and the Common Language Runtime.

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[MSBuild](https://github.com/dotnet/msbuild) is the build platform for .NET and Visual Studio. MSBuild, provides an XML schema for a project file that controls how the build platform processes and builds software. Visual Studio uses MSBuild to perform team builds through Azure DevOps Server, but MSBuild can run without Visual Studio.

[Roslyn](https://docs.microsoft.com/dotnet/csharp/roslyn-sdk/) is a .NET compiler developed by Microsoft that provides C# and Visual Basic languages with rich code analysis APIs.

[Bot Framework](https://github.com/microsoft/botframework-sdk) is a framework developed by Microsoft that provides the most comprehensive experience for building conversation applications. Developers can model and build sophisticated conversation using their favorite programming languages including C#, JS, Python and Java or using Bot Framework Composer, an open-source, visual authoring canvas for developers and multi-disciplinary teams to design and build conversational experiences with Language.

[Uno Platform](https://platform.uno/) is a Universal Windows Platform Bridge that allows UWP-based code (C# and XAML) to run on iOS, Android, macOS, WebAssembly, Linux and Windows 7. It provides the full definitions of the UWP [Windows 10 2004 (19041)](https://docs.microsoft.com/en-us/windows/uwp/whats-new/windows-10-build-19041), and the implementation of a growing number of parts of the UWP API, such as Windows.UI.Xaml, to enable UWP and WinUI applications to run on these platforms.

[Rider](https://www.jetbrains.com/rider/) is a fast and powerful, cross-platform .NET IDE devloped by JetBrains to develop .NET, ASP.NET, .NET Core, Xamarin; or Unity applications for Windows, Mac, Linux.

[Resharper](https://www.jetbrains.com/resharper/) is a [Visual Studio](https://visualstudio.microsoft.com/) Extension for .NET Developers that has On-the-fly code quality analysis for C#, VB.NET, XAML, ASP.NET, ASP.NET MVC, JavaScript, TypeScript, CSS, HTML, and XML. Letting you know right away if your code needs to be improved.

[dotPeek](https://www.jetbrains.com/decompiler/) is a tool developed by JetBrains based on ReSharper's bundled decompiler. It can reliably decompile any .NET assembly into equivalent C# or CIL code.

[dotTrace](https://www.jetbrains.com/profiler/) is an .NET performance Profiler developed by Jet Brains. It helps users locate performance bottlenecks in a variety of .NET applications: desktop applications, .NET Core, ASP.NET, ASP.NET Core applications hosted on IIS or IIS Express web servers, Silverlight, WCF services, Windows services, Universal Windows Platform applications, and unit tests.

[dotMemory](https://www.jetbrains.com/dotmemory/) is an .NET memory Profiler developed by Jet Brains. It allows the user to analyze memory usage in a variety of .NET and .NET Core applications: desktop applications, Windows services, ASP.NET web applications, IIS, IIS Express, arbitrary .NET processes, and more.

[dotCover](https://www.jetbrains.com/dotcover/) is an .NET unit test runner and code coverage tool developed by Jet Brains. It helps the user figure out on-the-fly which unit tests are affected by your latest code changes, and automatically re-runs the affected tests for you. The continuous testing mode can be switched on for any unit test session.

[Json.NET](https://www.newtonsoft.com/json) is a popular high-performance JSON framework for .NET.

[Quasar](https://github.com/quasar/Quasar) is a fast and light-weight remote administration tool coded in C#. The usage ranges from user support through day-to-day administrative work to employee monitoring. Providing high stability and an easy-to-use user interface, Quasar is the perfect remote administration solution for you.

[CodeMaid](https://github.com/codecadwallader/codemaid) is an open source Visual Studio extension to cleanup and simplify our C#, C++, F#, VB, PHP, PowerShell, JSON, XAML, XML, ASP, HTML, CSS, LESS, SCSS, JavaScript and TypeScript coding.

[.NET Fiddle](https://dotnetfiddle.net/) is an advanced online compiler for C# that allows you to create, run and share your code online.

[Octopus Deploy](https://octopus.com/) is a single place for your team to manage releases, automate deployments, and automate the runbooks that keeps your software operating.

[Appveyor](https://ci.appveyor.com/) is a cloud-based continuous integration system that integrates natively with your source control and allows CI configuration files to live alongside your projects.

[AppHarbor](https://appharbor.com/) is a .NET Platform-as-a-Service that let's developers deploy and scale any standard .NET application to the cloud.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[AutoRest](https://github.com/Azure/autorest) is a tool generates client libraries for accessing RESTful web services using the [OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) format. It Supports C#, PowerShell, Go, Java, Node.js, TypeScript, Python, Ruby.

[Markdig](https://github.com/lunet-io/markdig) is a fast, powerful, [CommonMark](https://commonmark.org/) compliant, extensible Markdown processor for .NET.


# F# Development

[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306464-da548100-ff27-11ea-8934-e9830a549cf1.png">
  <br />
</p>

**[Start building with F# on Azure](https://docs.microsoft.com/en-us/dotnet/fsharp/using-fsharp-on-azure/)**

**[F# Documentation](https://docs.microsoft.com/en-us/dotnet/fsharp/)**

##  F# Learning Resources

[F#](https://fsharp.org/) is a mature, open source, cross-platform, functional-first programming language. It empowers users and organizations to tackle complex computing problems with simple, maintainable and robust code.

[What is F#](https://docs.microsoft.com/en-us/dotnet/fsharp/what-is-fsharp)

[F#, the Functional programming for .NET](https://dotnet.microsoft.com/languages/fsharp)

[Cloud Programming with F#](https://fsharp.org/guides/cloud/)

[F# style guide](https://docs.microsoft.com/en-us/dotnet/fsharp/style-guide/)

[F# Programming Wikibook](http://en.wikibooks.org/wiki/Programming:F_Sharp)

[F# Developer Network (FSDN)](http://fsdn.azurewebsites.net/)

[Learning F# from The F# Software Foundation ](https://fsharp.org/learn/)

[F# Programming groups | Meetup](https://www.meetup.com/topics/f-programming/)

## F# Tools

[Python.NET](http://pythonnet.github.io/) is a package that gives Python programmers nearly seamless integration with the .NET Common Language Runtime (CLR) and provides a powerful application scripting tool for .NET developers. It allows Python code to interact with the CLR, and may also be used to embed Python into a .NET application.

[Fable](https://fable.io) is an F# to JavaScript compiler powered by [Babel](https://babeljs.io/), designed to make F# a first-class citizen of the JavaScript ecosystem.

[.NET for Apache Spark](https://dot.net/spark) provides high performance APIs for using Apache Spark from C# and F#. With these .NET APIs, you can access the most popular Dataframe and SparkSQL aspects of Apache Spark, for working with structured data, and Spark Structured Streaming, for working with streaming data. .NET for Apache Spark runs on Windows, Linux, and macOS using .NET Core, or Windows using .NET Framework. It also runs on all major cloud providers including [Azure HDInsight Spark](https://github.com/dotnet/spark/blob/master/deployment/README.md#azure-hdinsight-spark), [Amazon EMR Spark](https://github.com/dotnet/spark/blob/master/deployment/README.md#amazon-emr-spark), [AWS](https://github.com/dotnet/spark/blob/master/deployment/README.md#databricks) & [Azure](https://github.com/dotnet/spark/blob/master/deployment/README.md#databricks) Databricks.

[Giraffe](https://giraffe.wiki/) is a functional ASP.NET Core micro web framework for building rich web applications.

[Suave](https://suave.io/) is a simple web development F# library providing a lightweight web server and a set of combinators to manipulate route flow and task composition. Suave supports Websocket, HTTPS, multiple TCP/IP bindings, Basic Access Authentication, Keep-Alive.

[FsCheck](https://fscheck.github.io/FsCheck/) is a tool for testing .NET programs automatically. The programmer provides a specification of the program, in the form of properties which functions, methods or objects should satisfy, and FsCheck then tests that the properties hold in a large number of randomly generated cases.

[Elmish](https://elmish.github.io/elmish/) implements core abstractions for F# apps that can be used to build applications following the “model view update” style of architecture made famous by Elm. The library however does not model any "view" and is intended for use in conjuction with a DOM/renderer, like React/ReactNative or VirtualDOM.

[Saturn](https://saturnframework.org/) is a web development framework written in F# which implements the server-side MVC pattern. Many of its components and concepts will seem familiar to anyone with experience in other web frameworks like Ruby on Rails or Python’s Django.

[Pulumi](https://www.pulumi.com/) is Infrastructure as Code SDK is the easiest way to create and deploy cloud software that use containers, serverless functions, hosted services, and infrastructure, on any cloud. Simply write code in your favorite language and Pulumi will automatically provisions and manages your AWS, Azure, Google Cloud Platform, and/or Kubernetes resources, using an infrastructure-as-code approach.

[FsPickler](https://github.com/mbraceproject/FsPickler) is a serialization library that facilitates the distribution of .NET objects. The implementation focuses on performance and completeness in supported types, including F# types. It supports multiple, pluggable serialization formats including Binary, Xml, JSON and BSON. The library is based on the functional programming concept of [pickler combinators](https://www.microsoft.com/en-us/research/publication/functional-pearl-pickler-combinators/) which has been adapted to accommodate the object oriented nature of the .NET framework.

[Paket](https://fsprojects.github.io/Paket/) is a dependency manager for .NET with support for NuGet packages and git repositories.

[Fantomas](https://fsprojects.github.io/fantomas-tools/#/fantomas/preview) is a F# source code formatter.

[SQLProvider](http://fsprojects.github.io/SQLProvider) is a general F# SQL database erasing type provider, supporting LINQ queries, schema exploration, individuals, and CRUD operations.

[FsUnit](http://fsprojects.github.io/FsUnit/) makes unit-testing with F# more enjoyable. It adds a special syntax to your favorite .NET testing framework.

#  Xaramin Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127785363-75cd0a8d-928f-4669-9383-0b3a7110e08e.png">
  <br />
</p>

## Xaramin Learning Resources
[Back to the Top](https://github.com/mikeroyal/Xaramin-Guide#table-of-contents)

[Xamarin](https://docs.microsoft.com/en-us/xamarin/get-started/what-is-xamarin) is an open-source platform for building modern and performant applications for iOS, Android, and Windows with.NET. Xamarin is an abstraction layer that manages communication of shared code with underlying platform code. Xamarin runs in a managed environment that provides conveniences such as memory allocation and garbage collection.

[Xamarin documentation](https://docs.microsoft.com/en-us/xamarin/)

[Xaramin GitHub](https://github.com/xamarin)

[Visual Studio Tools for Xamarin](https://visualstudio.microsoft.com/xamarin/?WT.mc_id=dotnet-35129-website)

[NuGet Gallery | Xamarin](https://www.nuget.org/profiles/Xamarin)

[Xamarin App Development with Visual Studio](https://visualstudio.microsoft.com/xamarin/)

[Xamarin and Azure](https://azure.microsoft.com/en-us/features/xamarin/)

[Application Icons in Xamarin.iOS - Xamarin](https://docs.microsoft.com/en-us/xamarin/ios/app-fundamentals/images-icons/app-icons)

[Android & iOS Apps With Xamarin](https://dotnet.microsoft.com/apps/xamarin/mobile-apps)

[Xaramin Learn](https://dotnet.microsoft.com/learn/xamarin)

[Top Xamarin Courses Online | Udemy](https://www.udemy.com/topic/xamarin/)

[Xamarin: Build Native Cross Platform Apps with C# Codes | Udemy](https://www.udemy.com/course/xamarin-build-native-cross-platform-apps-with-c-codes/)

[Xamarin Online Training Courses | LinkedIn Learning](https://www.linkedin.com/learning/topics/xamarin)

[Online Xamarin Classes | Skillshare](https://www.skillshare.com/browse/xamarin)

## Xaramin Tools, Libraries, and Frameworks
[Back to the Top](https://github.com/mikeroyal/Xaramin-Guide#table-of-contents)

[Xamarin.Forms](https://dotnet.microsoft.com/apps/xamarin/xamarin-forms) is an open source cross-platform framework from Microsoft for building iOS, Android, & Windows apps with .NET from a single shared codebase.

[Rider](https://www.jetbrains.com/rider/) is a fast and powerful, cross-platform .NET IDE devloped by JetBrains to develop .NET, ASP.NET, .NET Core, Xamarin; or Unity applications for Windows, Mac, Linux.

[Resharper](https://www.jetbrains.com/resharper/) is a [Visual Studio](https://visualstudio.microsoft.com/) Extension for .NET Developers that has On-the-fly code quality analysis for C#, VB.NET, XAML, ASP.NET, ASP.NET MVC, JavaScript, TypeScript, CSS, HTML, and XML. Letting you know right away if your code needs to be improved.

[SkiaSharp](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/graphics/skiasharp/?WT.mc_id=dotnet-35129-website) is a 2D graphics system for .NET and C# powered by the open-source Skia graphics engine that is used extensively in Google products. This can be use in your Xamarin.Forms applications to draw 2D vector graphics, bitmaps, and text.

[MonoGame](https://github.com/MonoGame/MonoGame) is a cross-platform gaming framework based on Microsoft's XNA framework that's extremely easy to learn. Best of all, games you build with MonoGame will run on iOS, Android, Mac OS X, tvOS, Windows, Linux, PlayStation 4, and more—write once, play anywhere.

[Stride](https://stride3d.net/) is an open-source C# game engine for realistic rendering and VR. The engine is highly modular and aims at giving game makers more flexibility in their development. Stride comes with an editor that allows you to create and manage the content of your games or applications visually and intuitively.

[Wave Engine](https://waveengine.net) is a  graphics development engine for business and industry. Build high-quality 3D and 2D solutions and deploy to any platform.

[FlatRedBall](https://flatredball.com) is a cross-platform game engine, focused on 2D game development and proven across multiple shipped game projects. It’s a perfect choice for small indies or large teams.

[App Builder](http://www.getappbuilder.com/) is a complete IDE for Microsoft Windows which allows to create HTML5 and native apps without programming knowledge. Offers dozens of controls and actions ready to be used in your apps and lot of app samples to learn it.

[Monaca](https://monaca.io/) is a comprehensive cloud-powered and framework-agnostic set of tools Monaca supports both online and offline development, debugging with live-reload feature and cloud build experience.

[Onsen UI](http://onsen.io/) is a custom Elements-based HTML5 framework offers a large selection of components and responsive layout support. Onsen UI lets you create professionally designed multiplatform apps without acquiring additional skillset.

# PowerShell Development

[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297904-9918fe00-a111-11eb-887c-774b939f1bdf.png">
  <br />
</p>


## PowerShell Learning Resources

[Windows Remote Management in Ansible using PowerShell](https://docs.ansible.com/ansible/latest/user_guide/windows_winrm.html)

[Getting Started with PowerShell](https://docs.microsoft.com/en-us/powershell/)

[Start building with PowerShell on Azure](https://docs.microsoft.com/en-us/powershell/azure/install-az-ps)

[Azure PowerShell Documentation](https://docs.microsoft.com/en-us/powershell/azure/)

[PowerShell in Azure Cloud Shell](https://aka.ms/cloudshell/powershell-docs)

[Azure Functions using PowerShell](https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-first-function-vs-code?pivots=programming-language-powershell)

[Azure Automation runbooks](https://docs.microsoft.com/en-us/azure/automation/automation-runbook-types)

[Using Visual Studio Code for PowerShell Development](https://docs.microsoft.com/en-us/powershell/scripting/dev-cross-plat/vscode/using-vscode?view=powershell-7)

[Integrated Terminal in Visual Studio Code](https://code.visualstudio.com/docs/editor/integrated-terminal)

[AWS Tools for Windows PowerShell](https://aws.amazon.com/powershell/)

[Start building with PowerShell on Google Cloud](https://cloud.google.com/powershell/)

[PowerShell Documentation](https://cloud.google.com/powershell/docs/)

[PowerShell Best Practices and Style Guide](https://poshcode.gitbooks.io/powershell-practice-and-style)


## PowerShell Tools

[PowerShell Core](https://microsoft.com/PowerShell) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (JSON, CSV, XML, etc.), REST APIs, and object models. It also includes a command-line shell, an associated scripting language and a framework for processing cmdlets.

[Azure PowerShell](https://docs.microsoft.com/en-us/powershell/azure/overview) is a set of cmdlets for managing Microsoft Azure resources directly from the PowerShell command line.

[Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/learn/modules/get-started-with-windows-subsystem-for-linux/) is a compatibility layer developed by Microsoft for running Linux binary executables in a Executable/Linkable Format natively on Windows 10 and Windows Server.

[AWS Shell](https://aws.amazon.com/cli/) is a command-line shell program that provides convenience and productivity features to help both new and advanced users of the AWS Command Line Interface.

[Google Cloud Shell](https://cloud.google.com/shell/) is a free admin machine with browser-based command-line access for managing your infrastructure and applications on Google Cloud Platform.


# TypeScript Development

[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93133287-d1dc8a80-f68b-11ea-94d3-bba83dd5b0bb.png">
  <br />

</p>

**[Start building with TypeScript on Azure](https://aka.ms/azsdk/js)**

**[TypeScript Documentation](https://aka.ms/azsdk/js/docs)**

## TypeScript Learning Resources

[TypeScript](https://www.typescriptlang.org) is a language for application-scale JavaScript. TypeScript adds optional types to JavaScript that support tools for large-scale JavaScript applications for any browser, for any host, on any OS. TypeScript compiles to readable, standards-based JavaScript.

[TypeScript support for Webpack](https://webpack.js.org/guides/typescript/)

[TypeScript Support for Nuxt.js](https://typescript.nuxtjs.org)

[TypeScript Support for Vue.js](https://vuejs.org/v2/guide/typescript.html)

[TypeScript Support for React Native](https://reactnative.dev/docs/typescript)

[TypeScript Support for Angular](https://angular.io/guide/typescript-configuration)

[Ionic/TypeScript Starter Project](http://justin-credible.github.io/Ionic-TypeScript-Starter/)

[GitHub Actions for JavaScript and TypeScript](https://docs.github.com/en/actions/language-and-framework-guides/github-actions-for-javascript-and-typescript)

## Tools

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[ReSharper](https://www.jetbrains.com/resharper/) is a Visual Studio Extension for .NET Developers. It comes with code quality analysis, which is available in C#, VB.NET, XAML, ASP.NET, ASP.NET MVC, JavaScript, TypeScript, CSS, HTML, and XML. You'll know right away if your code needs to be improved. ReSharper is one of many powerful tools developed by [JetBrains](https://www.jetbrains.com).

[ts-migrate](https://github.com/airbnb/ts-migrate) is a tool for helping migrate code to TypeScript. It takes a JavaScript, or a partial TypeScript, project in and gives a compiling TypeScript project out. ts-migrate is intended to accelerate the TypeScript migration process. The resulting code will pass the build, but a followup is required to improve type safety.

[Deno](https://deno.land) is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.

[gulp-typescript](https://github.com/ivogabe/gulp-typescript) is an TypeScript compiler for gulp with incremental compilation support.

[React](https://reactjs.org/) is a declarative, efficient, and flexible JavaScript library for building user interfaces.

[React Native](https://reactnative.dev) is a framework for building native apps for iOS and Android with React.

[Vue.js](http://vuejs.org/) is a progressive, incrementally-adoptable JavaScript framework for building UI on the web.

[Angular](https://www.angular.io/) is a development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages.

[Ionic Framework](https://ionicframework.com/) is a powerful cross-platform UI toolkit for building native-quality iOS, Android, and Progressive Web Apps with HTML, CSS, and JavaScript.

[Stencil](https://stenciljs.com/) is a simple compiler for generating Web Components and static site generated progressive web apps (PWA). Stencil was built by the Ionic team for its next generation of performant mobile and desktop Web Components.

[Storybook](https://storybook.js.org/) is a development environment for UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components.It works with React, Vue, Angular, Ember, and other web frameworks.

[Prettier](https://prettier.io/) is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

[Nest](https://nestjs.com/) is a framework for building efficient, scalable [Node.js](http://nodejs.org/) server-side applications. It is built with TypeScript and combines elements of Object Oriented Programming(OOP), Functional Programming, and Functional Reactive Programming(FRP).

[Definitely Typed](https://github.com/DefinitelyTyped/DefinitelyTyped) is a repository for high quality TypeScript type definitions.

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[NativeScript](https://www.nativescript.org/) empowers you to access native APIs from JavaScript directly. The framework currently provides iOS and Android runtimes for rich mobile development and can be utilized in a number of diverse use cases.

[AssemblyScript](https://assemblyscript.org/) compiles a strict variant of TypeScript to [WebAssembly](http://webassembly.org/) using [Binaryen](https://github.com/WebAssembly/binaryen).

[React Hook Form](https://react-hook-form.com/) is a performant, flexible and extensible forms with easy to use validation(Web + React Native).

[Apollo Client](https://apollographql.com/client) is a fully-featured caching GraphQL client with integrations for React, Angular, and more. It allows you to easily build UI components that fetch data via GraphQL.

[TensorFlow.js](https://js.tensorflow.org/) is an open-source WebGL hardware-accelerated JavaScript library for training and deploying machine learning models.

[Rome](https://romefrontend.dev/) is a linter, compiler, bundler, and [more](https://romefrontend.dev/#development-status) for JavaScript, TypeScript, JSON, HTML, Markdown, and CSS.

[Eclipse Theia](https://github.com/eclipse-theia/theia) is an extensible platform to develop full-fledged multi-language Cloud & Desktop IDE-like products with state-of-the-art web technologies.

[InversifyJS](https://github.com/inversify/InversifyJS) is a powerful and lightweight inversion of control(IoC) container for JavaScript & Node.js apps powered by TypeScript. An IoC container uses a class constructor to identify and inject its dependencies.

[Gatsby](https://www.gatsbyjs.com/) is a free and open source framework based on React that helps developers build blazing fast websites and apps.

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavavScript.

[TypeScript ESLint](https://typescript-eslint.io/) is a monorepo for all the tooling which enables ESLint to support TypeScript.

[TS node](https://github.com/TypeStrong/ts-node) is a TypeScript execution and REPL for node.js.

# JavaScript Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/128940597-70d4dcdb-72eb-4004-a7ef-280cf77aa84b.png">
  <br />

</p>

## JavaScript Learning Resources

[JavaScript](https://www.ecma-international.org/publications-and-standards/standards/ecma-262/) is a programming language that conforms to the [ECMAScript specification](https://262.ecma-international.org/). JavaScript is a high-level language, often [Just-In-Time(JIT) compiled](https://en.wikipedia.org/wiki/Just-in-time_compilation), and [multi-paradigm](https://en.wikipedia.org/wiki/Multi-paradigm_programming_language).

[ECMAScript](https://262.ecma-international.org/) is a scripting language specification on which JavaScript is based. Ecma International is in charge of standardizing ECMAScript.

[Top JavaScript Courses Online | Coursera](https://www.coursera.org/courses?query=javascript)

[HTML, CSS, and Javascript for Web Developers Course | Coursera](https://www.coursera.org/learn/html-css-javascript-for-web-developers)

[Top JavaScript Courses Online | Udemy](https://www.udemy.com/topic/javascript/)

[Machine Learning with Javascript Course | Udemy](https://www.udemy.com/course/machine-learning-with-javascript/)

[Learn JavaScript with Online Courses and Classes | edX](https://www.edx.org/learn/javascript)

[Intro to JavaScript Courses | Udacity](https://www.udacity.com/course/intro-to-javascript--ud803)

[JavaScript Online Training Courses | LinkedIn Learning](https://www.linkedin.com/learning/topics/javascript)

[JavaScript Tutorial - W3Schools](https://www.w3schools.com/js/DEFAULT.asp)

[JavaScript Tutorial: Learning JavaScript Course | Codecademy](https://www.codecademy.com/learn/introduction-to-javascript)

[Online JavaScript Courses | Harvard University](https://online-learning.harvard.edu/subject/javascript)

[JavaScript Programming with Visual Studio Code](https://code.visualstudio.com/Docs/languages/javascript)

[Google's JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)

[Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

## JavaScript Tools, Libraries, and Frameworks

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[JavaScriptCore](https://developer.apple.com/documentation/javascriptcore) is Apple's framework that provides the ability to evaluate JavaScript programs from within Swift, Objective-C, and C-based apps. You can also use JavaScriptCore to insert custom objects into the JavaScript environment.

[React.js](https://reactjs.org/) is a declarative, efficient, and flexible JavaScript library for building user interfaces.

[React Native](https://reactnative.dev) is a framework for building native apps for iOS and Android with React.

[Gatsby](https://www.gatsbyjs.com/) is a free and open source framework based on React that helps developers build blazing fast websites and apps.

[Ember.js](https://emberjs.com/) is a JavaScript framework that greatly reduces the time, effort and resources needed to build any web application. It is focused on making you, the developer, as productive as possible by doing all the common, repetitive, yet essential, tasks involved in most web development projects.

[Nest.js](https://nestjs.com/) is a framework for building efficient, scalable [Node.js](http://nodejs.org/) server-side applications. It uses modern JavaScript, is built with TypeScript (preserves compatibility with pure JavaScript) and combines elements of OOP (Object Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming).

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavaScript.

[Next.js](https://github.com/vercel/next.js) is a React Framework for production gives you the best developer experience with all the features needed for production such as hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching, and more.

[Angular](https://www.angular.io/) is a development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages developed by Google.

[AngularJS](https://angularjs.org/) is a structural JavaScript MVW Framework for dynamic web apps that lets you extend HTML's syntax to express your application's components clearly and easily.

[Vue.js](http://vuejs.org/) is a progressive, incrementally-adoptable JavaScript framework for building UI on the web.

[Svelte](https://svelte.dev/) is a radical new approach to building user interfaces. Whereas traditional frameworks like React and Vue do the bulk of their work in the browser, Svelte shifts that work into a compile step that happens when you build your app.

[Node.js](https://nodejs.org/) is a JavaScript runtime built on Chrome's V8 JavaScript engine that lets developers write command line tools and server-side scripts outside of a browser.

[Apache Cordova](https://cordova.apache.org) is a mobile application development framework. It allows you to use standard web technologies such as HTML5, CSS3, and JavaScript for cross-platform development, avoiding each mobile platform's native development language.

[Ionic Framework](https://ionicframework.com/) is a front-end SDK for building cross-platform mobile apps. Built on top of [Angular](https://angular.io/) and [Apache Cordova](https://cordova.apache.org/), Ionic also provides a platform for integrating services like push notifications and analytics.

[Capacitor](https://capacitorjs.com/) is a cross-platform JavaScript API and code execution layer that makes it easy to call Native SDKs from web code and to write custom native plugins that your app may need. Additionally, Capacitor provides first-class Progressive Web App support so you can write one app and deploy it to the app stores and the mobile web.

[jQuery](https://jquery.com/) is a fast and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of web browsers.

[Backbone.js](https://backbonejs.org/) is a JavaScript library that gives structure to web applications by providing models with key-value binding and custom events, collections with a rich API of enumerable functions, views with declarative event handling, and connects it all to your existing API over a RESTful JSON interface.

[Electron](https://electronjs.org/) is a framework lets you write cross-platform desktop applications using JavaScript, HTML and CSS. It is based on [Node.js](https://nodejs.org/) and [Chromium](https://www.chromium.org/) and is used by the [Atom editor](https://github.com/atom/atom) and many other [apps](https://electronjs.org/apps).

[HTML (HyperText Markup Language)](https://developer.mozilla.org/en-US/docs/Web/HTML) is the basic building blocks of the Web. It defines the meaning and structure of web content along with other technologies used to describe a web page's appearance/presentation using CSS or functionality/behavior using JavaScript.

[Cascading Style Sheets (CSS)](https://developer.mozilla.org/en-US/docs/Web/CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG, MathML or XHTML). CSS also describes how elements should be rendered on screen, on paper, in speech, or on other media.

[axios](https://github.com/axios/axios) is a promise based HTTP client for the browser and node.js.

[React Starter Kit](https://www.reactstarterkit.com/) is an isomorphic web app boilerplate for web development built on top of [Node.js](https://nodejs.org/), [Express](http://expressjs.com/), [GraphQL](http://graphql.org/) and [React](https://facebook.github.io/react/), containing modern web development tools such as [Webpack](https://webpack.github.io/), [Babel](https://babeljs.io/) and [Browsersync](https://www.browsersync.io/). Helping you to stay productive following the best practices.

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[Enzyme](https://github.com/enzymejs/enzyme) is a JavaScript Testing utility for React that makes it easier to test your React Components' output. The user can also manipulate, traverse, and in some ways simulate runtime given the output.

[RxDB](https://github.com/pubkey/rxdb) is a NoSQL-database for JavaScript Applications like Websites, hybrid Apps, Electron-Apps, Progressive Web Apps and NodeJs.

[Redux](https://github.com/reduxjs/redux) is a predictable state container for JavaScript apps.

[Inferno](https://infernojs.org/) is an insanely fast, React-like library for building high-performance user interfaces on both the client and server.

[Expo](https://github.com/expo/expo) is an open-source platform for making universal native apps with React.

### JavaScript Libraries for Machine Learning

[TensorFlow.js](https://www.tensorflow.org/js) is a library for machine learning in JavaScript. Develop ML models in JavaScript, and use ML directly in the browser or in Node.js.

[Brain.js](https://brain.js.org/) is a JavaScript library that makes it easy to understand GPU accelerated Neural Networks because it hides the complexity of the mathematics. Brain.js provides multiple neural network implementations as different neural nets that can be trained to do different tasks well.

[Natural](https://github.com/NaturalNode/natural) is a general natural language facility for nodejs. It offers a broad range of functionalities for [Natural Language Processing](https://www.ibm.com/cloud/learn/natural-language-processing).

[ConvNetJS](https://cs.stanford.edu/people/karpathy/convnetjs/) is a Javascript library for training Deep Learning models (Neural Networks) entirely in your browser. No software requirements, compilers, installations, or GPUs.

[Ml.js](https://github.com/mljs/ml) is a JavaScript library that provides Machine learning tools in JavaScript.

[Neuro.js](https://neuro.js.org) is a JavaScript library for developing and training ML models in JavaScript, and deploying in browser or on Node.js.

[Stdlib](https://stdlib.io/) is a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing applications. The library provides a collection of robust, high performance libraries for mathematics, statistics, data processing, streams, and more and includes many of the utilities you would expect from a standard library.

[DeepForge](https://github.com/deepforge-dev/deepforge) is an open-source visual development environment for deep learning providing end-to-end support for creating deep learning models.

[Synaptic](https://github.com/cazala/synaptic) is a javascript neural network library for node.js and the browser, its generalized algorithm is architecture-free, so you can build and train basically any type of first order or even second order neural network architectures. This library includes a few built-in architectures like multilayer perceptrons, multilayer long-short term memory networks (LSTM), liquid state machines or Hopfield networks, and a trainer capable of training any given network.

[Deeplearn.js](https://www.npmjs.com/package/deeplearn) is an open source hardware-accelerated JavaScript library for machine intelligence. It brings performant machine learning building blocks to the web, allowing you to train neural networks in a browser or run pre-trained models in inference mode.

[WebDNN](https://github.com/mil-tokyo/webdnn) is the fastest Deep Neural Networks(DNN) running framework for the Web Browser.

[Mind](https://github.com/stevenmiller888/mind) is a flexible neural network library for Node.js and the browser.

# React Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/100526624-7ba5c080-317f-11eb-8bf6-6fedf59480e1.png">
  <br />
</p>

## React Learning Resources

[React](https://reactjs.org/) is a declarative, efficient, and flexible JavaScript library for building user interfaces.

[Getting Started with React](https://reactjs.org/docs/getting-started.html)

[React JavaScript Tutorial in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/reactjs-tutorial)

[React Community Resources](https://reactjs.org/community/support.html)

[React Courses on Coursera](https://www.coursera.org/courses?query=react)

[React Courses on Udemy](https://www.udemy.com/topic/react/)

[React Nanodegree program on Udacity](https://www.udacity.com/course/react-nanodegree--nd019)

[Becoming a React Developer Learning Path on LinkedIn Learning](https://www.linkedin.com/learning/paths/become-a-react-developer)

[Learning ReactJS on Codecademy](https://www.codecademy.com/learn/react-101)

[React Tutorials and Training Courses on Pluralsight](https://www.pluralsight.com/browse/software-development/react)

[Introduction to React Course on Cloud Academy](https://cloudacademy.com/course/introduction-toreact/development-environment-set-up/)

## React Tools and Frameworks

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[React Native](https://reactnative.dev) is a framework for building native apps for iOS and Android with React.

[Gatsby](https://www.gatsbyjs.com/) is a free and open source framework based on React that helps developers build blazing fast websites and apps.

[React Starter Kit](https://www.reactstarterkit.com/) is an isomorphic web app boilerplate for web development built on top of [Node.js](https://nodejs.org/), [Express](http://expressjs.com/), [GraphQL](http://graphql.org/) and [React](https://facebook.github.io/react/), containing modern web development tools such as [Webpack](https://webpack.github.io/), [Babel](https://babeljs.io/) and [Browsersync](https://www.browsersync.io/). Helping you to stay productive following the best practices.

[React Hook Form](https://react-hook-form.com/) is a performant, flexible and extensible forms with easy to use validation(Web + React Native).

[GraphQL](https://graphql.org/) is a query language for APIs and a runtime for fulfilling those queries with your existing data. It has support in Java, JavaScript, Ruby, Scala, and other programming languages.

[Apollo Client](https://apollographql.com/client) is a fully-featured caching GraphQL client with integrations for React, Angular, and more. It allows you to easily build UI components that fetch data via GraphQL.

[Nest](https://nestjs.com/) is a framework for building efficient, scalable [Node.js](http://nodejs.org/) server-side applications. It uses modern JavaScript, is built with TypeScript (preserves compatibility with pure JavaScript) and combines elements of OOP (Object Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming).

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavavScript.

[mysqljs](https://github.com/mysqljs/mysql) is a pure node.js JavaScript Client implementing the MySQL protocol.

[axios](https://github.com/axios/axios) is a promise based HTTP client for the browser and node.js.

[Storybook](https://storybook.js.org/) is a development environment for UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components.It works with React, Vue, Angular, Ember, and other web frameworks.

[Next.js](https://github.com/vercel/next.js) is a React Framework for production gives you the best developer experience with all the features needed for production such as hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching, and more.

[React Boilerplate](https://www.reactboilerplate.com/) is a highly scalable, offline-first foundation with the best developer experience and a focus on performance and best practices.

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[Enzyme](https://github.com/enzymejs/enzyme) is a JavaScript Testing utility for React that makes it easier to test your React Components' output. The user can also manipulate, traverse, and in some ways simulate runtime given the output.

[RxDB](https://github.com/pubkey/rxdb) is a NoSQL-database for JavaScript Applications like Websites, hybrid Apps, Electron-Apps, Progressive Web Apps and NodeJs.

[Redux](https://github.com/reduxjs/redux) is a predictable state container for JavaScript apps.

[Inferno](https://infernojs.org/) is an insanely fast, React-like library for building high-performance user interfaces on both the client and server.

[Expo](https://github.com/expo/expo) is an open-source platform for making universal native apps with React.

[React Native Windows](https://microsoft.github.io/react-native-windows/) is a ramework for building native Windows apps with React. [React Native](https://reactnative.dev/) is a framework developed by Facebook that enables you to build world-class application experiences on native platforms using a consistent developer experience based on JavaScript and React.

[ReactiveUI](https://reactiveui.net/) is a composable, cross-platform model-view-viewmodel framework for all .NET platforms that is inspired by functional reactive programming, which is a paradigm that allows you to abstract mutable state away from your user interfaces and express the idea around a feature in one readable place and improve the testability of your application.

[Ant Design](https://ant.design/) is an enterprise-class UI design language and React UI library.

[Material-UI](https://material-ui.com/) is a collection of [React](https://reactjs.org/) components for faster and simpler web development.

[Chakra UI](https://chakra-ui.com/) is  a set of accessible, reusable, and composable React components that make it super easy to create websites and apps.

# Ionic Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127785372-b5b20650-826d-4011-96f6-f768954bff86.png">
  <br />
</p>

## Ionic Learning Resources

[Back to the Top](https://github.com/mikeroyal/Ionic-Guide#table-of-contents)

[Ionic Framework](https://ionicframework.com/) is a front-end SDK for building cross-platform mobile apps. Built on top of [Angular](https://angular.io/) and [Apache Cordova](https://cordova.apache.org/), Ionic also provides a platform for integrating services like push notifications and analytics.

[Ionic GitHub](https://github.com/ionic-team)

[Ionic Framework - Enterprise Training](https://ionicframework.com/enterprise/training)

[Ionic Academy](https://ionicacademy.com/course-listing/)

[Top Ionic Courses Online | Udemy](https://www.udemy.com/topic/ionic/)

[Ionic React: Cross-Platform Mobile Development with Ionic 5 | Udemy](https://www.udemy.com/course/ionic-react/

[Ionic & Angular JS: Principles Of Mobile and Web Development](https://www.udemy.com/course/ionic-course/)

[Ionic: Getting Started | Pluralsight](https://www.pluralsight.com/courses/ionic-getting-started)

[Building Desktop Apps with Ionic and Electron | Pluralsight](https://www.pluralsight.com/courses/building-cross-platform-apps-ionic-electron)

[Ionic Essential Training | LinkedIn Learning](https://www.linkedin.com/learning/ionic-4-0-essential-training)

[JavaScript Programming with Visual Studio Code](https://code.visualstudio.com/Docs/languages/javascript)

[Google's JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)

[Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

## Ionic Tools, Libraries, and Frameworks

[Ionic command line interface (CLI)](https://github.com/ionic-team/ionic-cli) is the go-to tool for developing [Ionic](https://ionicframework.com/) apps.

[Stencil](https://stenciljs.com/) is a toolchain for building scalable, enterprise-ready component systems on top of TypeScript and Web Component standards. Stencil components can be distributed natively to [React](https://reactjs.org/), [Angular](https://angular.io/), [Vue.js](https://vuejs.org/), and traditional web developers from a single, framework-agnostic codebase.

[Stencil ESLint](https://github.com/ionic-team/stencil-eslint) is the ESLint rules specific to Stencil JS projects.

[Capacitor](https://capacitorjs.com/) is a cross-platform API and code execution layer that makes it easy to call Native SDKs from web code and to write custom native plugins that your app may need. Also, Capacitor provides first-class Progressive Web App(PWAs) support so you can write one app and deploy it to the app stores and the mobile web.

[Ionic Native](https://ionicframework.com/docs/native/) is a curated set of wrappers for Cordova plugins that make adding any native functionality you need to your [Ionic](https://ionicframework.com/) mobile app easy.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[Monaca](https://monaca.io/) is a comprehensive cloud-powered and framework-agnostic set of tools Monaca supports both online and offline development, debugging with live-reload feature and cloud build experience.

[Onsen UI](http://onsen.io/) is a custom Elements-based HTML5 framework offers a large selection of components and responsive layout support. Onsen UI lets you create professionally designed multiplatform apps without acquiring additional skillset.

[App Builder](http://www.getappbuilder.com/) is a complete IDE for Microsoft Windows which allows to create HTML5 and native apps without programming knowledge. Offers dozens of controls and actions ready to be used in your apps and lot of app samples to learn it.

[Storybook](https://storybook.js.org/) is a development environment for UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components.It works with React, Vue, Angular, Ember, and other web frameworks.

[Standard](https://standardjs.com/) is a JavaScript Style Guide, with linter & automatic code fixer.

[Framework7](http://www.idangero.us/framework7/) is a free and open source mobile HTML framework for developing hybrid mobile apps or web apps with iOS & Android native look and feel.

[NSB/AppStudio](https://www.nsbasic.com/) is an IDE for webapps/native apps. One step install includes complete PhoneGap integration, plus Bootstrap, jQuery Mobile and jqWidgets. Drag and Drop Designer. Easy programming in JavaScript or BASIC. Windows and MacOS.

[Mobiscroll](https://mobiscroll.com/) is a collection of cross platform UI controls for delivering polished iOS, Android & Windows Phone apps. Framework agnostic, use it with plain Javascript, jQuery, Angular, React or Knockout.

[Instabug](https://instabug.com/platforms/cordova) is a service that provides Cordova developers with a bug reporting and in-app feedback solution. With a one minute install guide, it enables users to seamlessly report bugs while automatically attaching details such as network logs, repro-steps, etc.

[Quasar](https://quasar.dev/) is a write code once and simultaneously deploy it as a website, Mobile / Electron App or Browser Extension. Yes, one codebase for all of them, helping you develop an app in record time by using a state-of-the-art CLI and backed by best-practice, blazing f...

[VoltBuilder](https://volt.build/) is a modern replacement for PhoneGap Build. Upload project and certificates, then download builds (or upload to store). Uses latest Apache Cordova and SDKs. There's nothing to install: just sign up and submit.

[VoltSigner](https://voltsigner.com/) is a free service to create Android and iOS signing certificates. Run completely in your local browser - nothing gets uploaded. Compatible with all build tools. Notably, it can produce iOS certificates on Windows.

[NPM](https://www.npmjs.com/) is the company behind Node package manager, the npm Registry, and npm CLI.

[node-gyp](https://github.com/nodejs/node-gyp) is a cross-platform command-line tool written in Node.js for compiling native addon modules for Node.js. It contains a vendored copy of the gyp-next project that was previously used by the Chromium team, extended to support the development of Node.js native addons.

[nvm ](https://github.com/nvm-sh/nvm) is a version manager for node.js, designed to be installed per-user, and invoked per-shell. nvm works on any POSIX-compliant shell (sh, dash, ksh, zsh, bash), in particular on these platforms: unix, macOS, and windows WSL.

[node-docker](https://hub.docker.com/_/node/) is the official Node.js docker image, made with love by the node community.

[Mocha](https://github.com/mochajs/mocha) is a simple, flexible, fun JavaScript test framework for Node.js & The Browser.

[AVA](https://github.com/avajs/ava) is a test runner for Node.js with a concise API, detailed error output, embrace of new language features and process isolation that lets you develop with confidence.

[egg](https://eggjs.org/) is a born to build better enterprise frameworks and apps with Node.js & Koa.

[Fastify](https://www.fastify.io/) is a fast and low overhead web framework, for Node.js.

[Express](https://expressjs.com/) is a fast, unopinionated, minimalist web framework for node.

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavavScript.

[NW.js](https://nwjs.io/) is an app runtime based on Chromium and node.js. You can write native apps in HTML and JavaScript with NW.js. It also lets you call Node.js modules directly from the DOM and enables a new way of writing native applications with all Web technologies.

[PM2](https://pm2.io/) is a production process manager for Node.js applications with a built-in load balancer. It allows you to keep applications alive forever, to reload them without downtime and to facilitate common system admin tasks.

[GraphQL](https://graphql.org/) is a query language for APIs and a runtime for fulfilling those queries with your existing data. It has support in Java, JavaScript, Ruby, Scala, and other programming languages.

[Apollo Client](https://apollographql.com/client) is a fully-featured caching GraphQL client with integrations for React, Angular, and more. It allows you to easily build UI components that fetch data via GraphQL.

[Nest](https://nestjs.com/) is a framework for building efficient, scalable [Node.js](http://nodejs.org/) server-side applications. It uses modern JavaScript, is built with TypeScript (preserves compatibility with pure JavaScript) and combines elements of OOP (Object Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming).

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavavScript.

[mysqljs](https://github.com/mysqljs/mysql) is a pure node.js JavaScript Client implementing the MySQL protocol.

[axios](https://github.com/axios/axios) is a promise based HTTP client for the browser and node.js.

[Next.js](https://github.com/vercel/next.js) is a React Framework for production gives you the best developer experience with all the features needed for production such as hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching, and more.

[React Starter Kit](https://www.reactstarterkit.com/) is an isomorphic web app boilerplate for web development built on top of [Node.js](https://nodejs.org/), [Express](http://expressjs.com/), [GraphQL](http://graphql.org/) and [React](https://facebook.github.io/react/), containing modern web development tools such as [Webpack](https://webpack.github.io/), [Babel](https://babeljs.io/) and [Browsersync](https://www.browsersync.io/). Helping you to stay productive following the best practices.

[React Boilerplate](https://www.reactboilerplate.com/) is a highly scalable, offline-first foundation with the best developer experience and a focus on performance and best practices.

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[Enzyme](https://github.com/enzymejs/enzyme) is a JavaScript Testing utility for React that makes it easier to test your React Components' output. The user can also manipulate, traverse, and in some ways simulate runtime given the output.

[RxDB](https://github.com/pubkey/rxdb) is a NoSQL-database for JavaScript Applications like Websites, hybrid Apps, Electron-Apps, Progressive Web Apps and NodeJs.

[Redux](https://github.com/reduxjs/redux) is a predictable state container for JavaScript apps.

[Inferno](https://infernojs.org/) is an insanely fast, React-like library for building high-performance user interfaces on both the client and server.

[Expo](https://github.com/expo/expo) is an open-source platform for making universal native apps with React.

[React Native Windows](https://microsoft.github.io/react-native-windows/) is a ramework for building native Windows apps with React. [React Native](https://reactnative.dev/) is a framework developed by Facebook that enables you to build world-class application experiences on native platforms using a consistent developer experience based on JavaScript and React.

[ReactiveUI](https://reactiveui.net/) is a composable, cross-platform model-view-viewmodel framework for all .NET platforms that is inspired by functional reactive programming, which is a paradigm that allows you to abstract mutable state away from your user interfaces and express the idea around a feature in one readable place and improve the testability of your application.

# Cordova Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/123559070-b8a25780-d74e-11eb-93e2-80f6f93e63c3.png">
  <br />
</p>

## Cordova Learning Resources

[Apache Cordova](https://cordova.apache.org) is a mobile application development framework. It allows you to use standard web technologies such as HTML5, CSS3, and JavaScript for cross-platform development, avoiding each mobile platform's native development language.

[Getting Started with Cordova](https://cordova.apache.org/#getstarted)

[Top Apache Cordova Courses on Udemy](https://www.udemy.com/topic/Apache-Cordova/)

[Apache Cordova - Building Hybrid Mobile App for Android & iOS Course on Udemy](https://www.udemy.com/course/apache-cordova/)

[Learning Apache Cordova Course on Linkedin Learning](https://www.linkedin.com/learning/learning-apache-cordova)

[Apache Cordova: Building Cross-Platform Mobile Apps Course on Linkedin Learning](https://www.linkedin.com/learning/apache-cordova-building-cross-platform-mobile-apps?trk=course_title&upsellOrderOrigin=default_guest_learning)

[Choosing a Cross-Platform Development Tool: Cordova, Ionic, React Native, Titanium, and Xamarin Course on Linkedin Learning](https://www.linkedin.com/learning/choosing-a-cross-platform-development-tool-cordova-ionic-react-native-titanium-and-xamarin?trk=learning-serp_learning_search-card&upsellOrderOrigin=default_guest_learning)

[Convert a web app to a Cordova project Course on Linkedin Learning](https://www.linkedin.com/learning/choosing-a-cross-platform-development-tool-cordova-ionic-react-native-titanium-and-xamarin/convert-a-web-app-to-a-cordova-project?trk=learning-serp_learning_search-card&upsellOrderOrigin=default_guest_learning)

[Build a Cordova app Course on Linkedin Learning](https://www.linkedin.com/learning/choosing-a-cross-platform-development-tool-cordova-ionic-react-native-titanium-and-xamarin/build-a-cordova-app?trk=learning-serp_learning_search-card&upsellOrderOrigin=default_guest_learning)

[JavaScript Programming with Visual Studio Code](https://code.visualstudio.com/Docs/languages/javascript)

[Google's JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)

[Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)


## Cordova Tools, Libraries and Frameworks

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[VSCode Cordova](https://github.com/Microsoft/vscode-cordova) is a Visual Studio Code extension providing intellisense, debug, and build support for Cordova and Ionic projects.

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[Ionic](https://ionicframework.com/) is a front-end SDK for building cross-platform mobile apps. Built on top of Angular, Ionic also provides a platform for integrating services like push notifications and analytics.

[Monaca](https://monaca.io/) is a comprehensive cloud-powered and framework-agnostic set of tools Monaca supports both online and offline development, debugging with live-reload feature and cloud build experience.

[Onsen UI](http://onsen.io/) is a custom Elements-based HTML5 framework offers a large selection of components and responsive layout support. Onsen UI lets you create professionally designed multiplatform apps without acquiring additional skillset.

[App Builder](http://www.getappbuilder.com/) is a complete IDE for Microsoft Windows which allows to create HTML5 and native apps without programming knowledge. Offers dozens of controls and actions ready to be used in your apps and lot of app samples to learn it.

[Framework7](http://www.idangero.us/framework7/) is a free and open source mobile HTML framework for developing hybrid mobile apps or web apps with iOS & Android native look and feel.

[NSB/AppStudio](https://www.nsbasic.com/) is an IDE for webapps/native apps. One step install includes complete PhoneGap integration, plus Bootstrap, jQuery Mobile and jqWidgets. Drag and Drop Designer. Easy programming in JavaScript or BASIC. Windows and MacOS.

[Mobiscroll](https://mobiscroll.com/) is a collection of cross platform UI controls for delivering polished iOS, Android & Windows Phone apps. Framework agnostic, use it with plain Javascript, jQuery, Angular, React or Knockout.

[Instabug](https://instabug.com/platforms/cordova) is a service that provides Cordova developers with a bug reporting and in-app feedback solution. With a one minute install guide, it enables users to seamlessly report bugs while automatically attaching details such as network logs, repro-steps, etc.

[Quasar](https://quasar.dev/) is a write code once and simultaneously deploy it as a website, Mobile / Electron App or Browser Extension. Yes, one codebase for all of them, helping you develop an app in record time by using a state-of-the-art CLI and backed by best-practice.

[VoltBuilder](https://volt.build/) is a modern replacement for PhoneGap Build. Upload project and certificates, then download builds (or upload to store). Uses latest Apache Cordova and SDKs. There's nothing to install: just sign up and submit.

[VoltSigner](https://voltsigner.com/) is a free service to create Android and iOS signing certificates. Run completely in your local browser - nothing gets uploaded. Compatible with all build tools. Notably, it can produce iOS certificates on Windows.

[NPM](https://www.npmjs.com/) is the company behind Node package manager, the npm Registry, and npm CLI.

[node-gyp](https://github.com/nodejs/node-gyp) is a cross-platform command-line tool written in Node.js for compiling native addon modules for Node.js. It contains a vendored copy of the gyp-next project that was previously used by the Chromium team, extended to support the development of Node.js native addons.

[nvm ](https://github.com/nvm-sh/nvm) is a version manager for node.js, designed to be installed per-user, and invoked per-shell. nvm works on any POSIX-compliant shell (sh, dash, ksh, zsh, bash), in particular on these platforms: unix, macOS, and windows WSL.

[node-docker](https://hub.docker.com/_/node/) is the official Node.js docker image, made with love by the node community.

[Mocha](https://github.com/mochajs/mocha) is a simple, flexible, fun JavaScript test framework for Node.js & The Browser.

[AVA](https://github.com/avajs/ava) is a test runner for Node.js with a concise API, detailed error output, embrace of new language features and process isolation that lets you develop with confidence.

[egg](https://eggjs.org/) is a born to build better enterprise frameworks and apps with Node.js & Koa.

[Fastify](https://www.fastify.io/) is a fast and low overhead web framework, for Node.js.

[Express](https://expressjs.com/) is a fast, unopinionated, minimalist web framework for node.

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavavScript.

[NW.js](https://nwjs.io/) is an app runtime based on Chromium and node.js. You can write native apps in HTML and JavaScript with NW.js. It also lets you call Node.js modules directly from the DOM and enables a new way of writing native applications with all Web technologies.

[PM2](https://pm2.io/) is a production process manager for Node.js applications with a built-in load balancer. It allows you to keep applications alive forever, to reload them without downtime and to facilitate common system admin tasks.

[GraphQL](https://graphql.org/) is a query language for APIs and a runtime for fulfilling those queries with your existing data. It has support in Java, JavaScript, Ruby, Scala, and other programming languages.

[Apollo Client](https://apollographql.com/client) is a fully-featured caching GraphQL client with integrations for React, Angular, and more. It allows you to easily build UI components that fetch data via GraphQL.

[Nest](https://nestjs.com/) is a framework for building efficient, scalable [Node.js](http://nodejs.org/) server-side applications. It uses modern JavaScript, is built with TypeScript (preserves compatibility with pure JavaScript) and combines elements of OOP (Object Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming).

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavavScript.

[mysqljs](https://github.com/mysqljs/mysql) is a pure node.js JavaScript Client implementing the MySQL protocol.

[axios](https://github.com/axios/axios) is a promise based HTTP client for the browser and node.js.

[Storybook](https://storybook.js.org/) is a development environment for UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components.It works with React, Vue, Angular, Ember, and other web frameworks.

[Next.js](https://github.com/vercel/next.js) is a React Framework for production gives you the best developer experience with all the features needed for production such as hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching, and more.

[Standard](https://standardjs.com/) is a JavaScript Style Guide, with linter & automatic code fixer.

[React Starter Kit](https://www.reactstarterkit.com/) is an isomorphic web app boilerplate for web development built on top of [Node.js](https://nodejs.org/), [Express](http://expressjs.com/), [GraphQL](http://graphql.org/) and [React](https://facebook.github.io/react/), containing modern web development tools such as [Webpack](https://webpack.github.io/), [Babel](https://babeljs.io/) and [Browsersync](https://www.browsersync.io/). Helping you to stay productive following the best practices.

[React Boilerplate](https://www.reactboilerplate.com/) is a highly scalable, offline-first foundation with the best developer experience and a focus on performance and best practices.

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[Enzyme](https://github.com/enzymejs/enzyme) is a JavaScript Testing utility for React that makes it easier to test your React Components' output. The user can also manipulate, traverse, and in some ways simulate runtime given the output.

[RxDB](https://github.com/pubkey/rxdb) is a NoSQL-database for JavaScript Applications like Websites, hybrid Apps, Electron-Apps, Progressive Web Apps and NodeJs.

[Redux](https://github.com/reduxjs/redux) is a predictable state container for JavaScript apps.

[Inferno](https://infernojs.org/) is an insanely fast, React-like library for building high-performance user interfaces on both the client and server.

[Expo](https://github.com/expo/expo) is an open-source platform for making universal native apps with React.

[React Native Windows](https://microsoft.github.io/react-native-windows/) is a ramework for building native Windows apps with React. [React Native](https://reactnative.dev/) is a framework developed by Facebook that enables you to build world-class application experiences on native platforms using a consistent developer experience based on JavaScript and React.

[ReactiveUI](https://reactiveui.net/) is a composable, cross-platform model-view-viewmodel framework for all .NET platforms that is inspired by functional reactive programming, which is a paradigm that allows you to abstract mutable state away from your user interfaces and express the idea around a feature in one readable place and improve the testability of your application.

# Angular Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/101415619-1b103500-389d-11eb-83f8-74f87abf5eaf.png">
  <br />
</p>

## Angular Learning Resources

[Angular](https://www.angular.io/) is a development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages developed by Google.

[Getting Started with Angular](https://angular.io/start)

[What Is AngularJS?](https://docs.angularjs.org/guide/introduction#!)

[Google's JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)

[Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

[AngularJS Tutorial on W3Schools](https://www.w3schools.com/angular/)

[Angular Certification - Become a certified Angular Developer](https://www.angulartraining.com/angular-certification.html)

[Angular University](https://angular-university.io)

[Angular Courses Online on Udemy](https://www.udemy.com/topic/angular/)

[Angular Courses Online on Coursera](https://www.coursera.org/search?query=angular&)

[Learn Angular with Online Courses and Lessons on edX](https://www.edx.org/learn/angular)

[Angular Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/angular-2)

[Learning AngularJS, including Angular directives from Codecademy](https://www.codecademy.com/learn/learn-angularjs)

[Learning Angular from Pluralsight](https://www.pluralsight.com/paths/angular)

[Ionic Angular Overview](https://ionicframework.com/docs/angular/overview)

[Angular Language Service for Visual Studio](https://devblogs.microsoft.com/visualstudio/angular-language-service-for-visual-studio/)

[Angular JavaScript Tutorial in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/angular-tutorial)

[Laravel and Angular](https://laravel-angular.io/docs/1/)

## Angular Tools and Frameworks

[Angular CLI](https://cli.angular.io/) is a command-line tool makes it easy to create an application that already works, right out of the box and follows all of Angular's best practices.

[Angular Material UI component library](https://material.angular.io/) is the Component infrastructure and Material Design components for Angular.

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[Storybook](https://storybook.js.org/) is a development environment for UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components.It works with React, Vue, Angular, Ember, and other web frameworks.

[AngularFire](https://firebaseopensource.com/projects/angular/angularfire2) is the official Angular library for [Firebase](https://firebase.google.com/).

[Apollo Angular](https://apollo-angular.com/) is a GraphQL Client for Angular Framework.

[GraphQL Code Generator](https://graphql-code-generator.com/) is a  tool for generating code based on a GraphQL schema and GraphQL operations. The project  currently support and maintain [plugins](https://graphql-code-generator.com/docs/plugins/index) (TypeScript, Flow, React, Angular, MongoDB, Stencil, Reason, and more).

[NgRx](https://ngrx.io/) is the Reactive libraries for Angular.

[RxDB](https://github.com/pubkey/rxdb) is a NoSQL-database for JavaScript Applications like Websites, hybrid Apps, Electron-Apps, Progressive Web Apps and NodeJs.

[Redux](https://github.com/reduxjs/redux) is a predictable state container for JavaScript apps.

[Protractor](https://angular.github.io/protractor) is an end-to-end test framework for Angular and AngularJS applications. Protractor is a [Node.js](http://nodejs.org/) program built on top of [WebDriverJS](https://github.com/SeleniumHQ/selenium/wiki/WebDriverJs).

[Onsen UI](https://onsen.io/) is an open source framework that makes it easy to create native-feeling Progressive Web Apps (PWAs) and hybrid apps. It provides bindings for Angular 1, 2, React and Vue.js.

[Nebular](https://github.com/akveo/nebular) is a customizable Angular 10 UI Library with a focus on beautiful design and ability to adapt it to your brand easily. It comes with 4 visual themes, a powerful theming engine with runtime theme switching, and support of custom css properties mode.

[PrimeNG](https://www.primefaces.org/angular) is the Most Complete Angular UI Component Library.

[Project Clarity](https://clarity.design) is an open source design system that brings together UX guidelines, an HTML/CSS framework, Angular components, and Web Components. Project Clarity is currently being developed by VMware.

[Angular Flex Layout](https://github.com/angular/flex-layout) is a sophisticated HTML UI layout for Angular applications; using Flexbox and a [Responsive API](https://github.com/angular/flex-layout/wiki/Responsive-API).

[UI-Grid](https://github.com/angular-ui/ui-grid) is an AngularJS data grid.

# Vue.js Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/102273501-41eeec80-3ed7-11eb-9ec7-cfc365d5baa8.png">
  <br />
</p>

## Vue.js Learning Resources

[Vue.js](http://vuejs.org/) is a progressive, incrementally-adoptable JavaScript framework for building UI on the web.

[Introduction to Vue.js](https://vuejs.org/v2/guide/)

[Vue.js API](https://vuejs.org/v2/api/)

[Introduction to Vue Test Utils](https://vue-test-utils.vuejs.org/)

[TypeScript Support for Vue.js](https://vuejs.org/v2/guide/typescript.html)

[Vue JavaScript Tutorial in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/vuejs-tutorial)

[Vue.js Plugins for JetBrains](https://plugins.jetbrains.com/plugin/9442-vue-js/versions)

[Introducing Storybook for VueJS](https://storybook.js.org/blog/introducing-storybook-for-vue/)

[Vue Mastery is the Ultimate Learning Resource for Vue.js](https://www.vuemastery.com/)

[Learn Vue.js from core-team members and industry experts on VueSchool](https://vueschool.io/)

[VueJS Courses on Udemy](https://www.udemy.com/topic/vue-js/)

[Learning Vue.js on Codecademy](https://www.codecademy.com/learn/learn-vue-js)

[VueJS Gitter](https://gitter.im/vuejs/vue)

[VueJS Forum](https://forum.vuejs.org)

[VueJS  Open Collective](https://opencollective.com/vuejs)

## Vue.js Tools and Frameworks

[Vue CLI](https://cli.vuejs.org/) is a standard tooling for Vue.js development that provides support for Babel, TypeScript, ESLint, PostCSS, PWA, Unit Testing & End-to-end Testing.

[Vue Router](https://router.vuejs.org/) is the official router for Vue.js. It deeply integrates with Vue.js core to make building Single Page Applications with Vue.js a breeze.

[VuePress](https://vuepress.vuejs.org/) is a tool that generates pre-rendered static HTML for each page, and runs as an SPA once a page is loaded.

[Vuefire](https://vuefire.vuejs.org/) is Firebase bindings for Vue.js & Vuex.

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[Element](https://github.com/ElemeFE/element) is a Vue.js 2.0 UI Toolkit for Web.

[Vuetify](https://vuetifyjs.com/) is a Material Component Framework for Vue.

[Buefy](https://buefy.org/) is a lightweight UI components for Vue.js based on Bulma.

[Storybook](https://storybook.js.org/) is a development environment for UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components.It works with React, Vue, Angular, Ember, and other web frameworks.

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[Apollo Client](https://apollographql.com/client) is a fully-featured caching GraphQL client with integrations for React, Angular, and more. It allows you to easily build UI components that fetch data via GraphQL.

[Vue-Apollo](http://apollo.vuejs.org/) is  the Apollo/GraphQL integration for VueJS.

[RxDB](https://github.com/pubkey/rxdb) is a NoSQL-database for JavaScript Applications like Websites, hybrid Apps, Electron-Apps, Progressive Web Apps and NodeJs.

[Redux](https://github.com/reduxjs/redux) is a predictable state container for JavaScript apps.

[Onsen UI](https://onsen.io/) is an open source framework that makes it easy to create native-feeling Progressive Web Apps (PWAs) and hybrid apps. It provides bindings for Angular 1, 2, React and Vue.js.

[Nest](https://nestjs.com/) is a framework for building efficient, scalable [Node.js](http://nodejs.org/) server-side applications. It uses modern JavaScript, is built with TypeScript (preserves compatibility with pure JavaScript) and combines elements of OOP (Object Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming).

[Hoppscotch](https://hoppscotch.io/) is a free, fast and beautiful API request builder used by 100k+ developers.

[Quasar](https://quasar.dev/) is a framework that builds high-performance VueJS user interfaces in record time. Such as responsive Single Page Apps, SSR Apps, PWAs, Browser extensions, Hybrid Mobile Apps and Electron Apps.

# Svelte Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/128940609-1d92fbc8-58d1-4723-a4c9-e382effe31f9.png">
  <br />
</p>

## Svelte Learning Resources

[Svelte](https://svelte.dev/) is a radical new approach to building user interfaces. Whereas traditional frameworks like React and Vue do the bulk of their work in the browser, Svelte shifts that work into a compile step that happens when you build your app.

[Svelte Tutorials](https://svelte.dev/tutorial/basics)

[Svelte Code Examples](https://svelte.dev/examples)

[Svelte API](https://svelte.dev/docs)

[Svelte REPL](https://svelte.dev/repl/hello-world)

[Getting started with Svelte - Learning web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Svelte_getting_started)

[JavaScript Programming with Visual Studio Code](https://code.visualstudio.com/Docs/languages/javascript)

[Google's JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)

[Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

## Svelte Tools, Libraries, and Frameworks

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[Svelte Language Tools](https://github.com/sveltejs/language-tools) is a library implementing the Language Server Protocol (LSP). LSP powers the VSCode extension.

[SvelteKit](https://github.com/sveltejs/kit) is a tool that makes it fast to build Svelte apps.

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[Enzyme](https://github.com/enzymejs/enzyme) is a JavaScript Testing utility for React that makes it easier to test your React Components' output. The user can also manipulate, traverse, and in some ways simulate runtime given the output.

[RxDB](https://github.com/pubkey/rxdb) is a NoSQL-database for JavaScript Applications like Websites, hybrid Apps, Electron-Apps, Progressive Web Apps and NodeJs.

[Redux](https://github.com/reduxjs/redux) is a predictable state container for JavaScript apps.

[Inferno](https://infernojs.org/) is an insanely fast, React-like library for building high-performance user interfaces on both the client and server.

# Node.js Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719688-0becd700-fb39-11ea-9b87-3d52f1828aee.png">
  <br />
</p>

## Node.js Learning Resources

[Node.js](https://nodejs.org/) is a JavaScript runtime built on Chrome's V8 JavaScript engine that lets developers write command line tools and server-side scripts outside of a browser.

[Node.js Build Working Group](https://github.com/nodejs/build) maintains and controls infrastructure used for continuous integration (CI), releases, benchmarks, web hosting (of nodejs.org and other Node.js web properties) and more.

[The OpenJS Foundation](https://openjsf.org/) is made up of 32 open source JavaScript projects including Appium, Dojo, Electron, jQuery, Node.js, and webpack. The foundation's mission is to support the healthy growth of JavaScript and web technologies by providing a neutral organization to host and sustain projects, as well as collaboratively fund activities that benefit the ecosystem as a whole.

[Set up NodeJS on WSL 2](https://docs.microsoft.com/en-us/windows/nodejs/setup-on-wsl2)

[Getting started with Node.js in Google Cloud](https://cloud.google.com/nodejs/getting-started)

[Getting Started with Node.js in AWS](https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/getting-started-nodejs.html)

[Node.js App Hosting & Deployment in Microsoft Azure](https://azure.microsoft.com/en-us/develop/nodejs/)

[The Node.js best practices list ](https://github.com/goldbergyoni/nodebestpractices)

[Introduction to Node.js by W3Schools](https://www.w3schools.com/nodejs/nodejs_intro.asp)

[The Node.js Community Committee](https://github.com/nodejs/community-committee)

[Node.js Mentorship Program Initiative](https://github.com/nodejs/mentorship)

[Node.js tutorial in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/nodejs-tutorial)

[Server-side Development with NodeJS, Express and MongoDB on Coursera](https://www.coursera.org/learn/server-side-nodejs)

## Node.js Tools, Libraries, and Frameworks

[NPM](https://www.npmjs.com/) is the company behind Node package manager, the npm Registry, and npm CLI.

[node-gyp](https://github.com/nodejs/node-gyp) is a cross-platform command-line tool written in Node.js for compiling native addon modules for Node.js. It contains a vendored copy of the gyp-next project that was previously used by the Chromium team, extended to support the development of Node.js native addons.

[nvm ](https://github.com/nvm-sh/nvm) is a version manager for node.js, designed to be installed per-user, and invoked per-shell. nvm works on any POSIX-compliant shell (sh, dash, ksh, zsh, bash), in particular on these platforms: unix, macOS, and windows WSL.

[node-docker](https://hub.docker.com/_/node/) is the official Node.js docker image, made with love by the node community.

[Mocha](https://github.com/mochajs/mocha) is a simple, flexible, fun JavaScript test framework for Node.js & The Browser.

[AVA](https://github.com/avajs/ava) is a test runner for Node.js with a concise API, detailed error output, embrace of new language features and process isolation that lets you develop with confidence.

[egg](https://eggjs.org/) is a born to build better enterprise frameworks and apps with Node.js & Koa.

[mysqljs](https://github.com/mysqljs/mysql) is a pure node.js JavaScript Client implementing the MySQL protocol.

[axios](https://github.com/axios/axios) is a promise based HTTP client for the browser and node.js.

[Fastify](https://www.fastify.io/) is a fast and low overhead web framework, for Node.js.

[Express](https://expressjs.com/) is a fast, unopinionated, minimalist web framework for node.

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavavScript.

[NW.js](https://nwjs.io/) is an app runtime based on Chromium and node.js. You can write native apps in HTML and JavaScript with NW.js. It also lets you call Node.js modules directly from the DOM and enables a new way of writing native applications with all Web technologies.

[PM2](https://pm2.io/) is a production process manager for Node.js applications with a built-in load balancer. It allows you to keep applications alive forever, to reload them without downtime and to facilitate common system admin tasks.

[NestJS](https://nestjs.com/) is a framework for building efficient, scalable Node.js web applications. It uses modern JavaScript, is built with TypeScript and combines elements of OOP (Object Oriented Progamming), FP (Functional Programming), and FRP (Functional Reactive Programming).

[jenkins-nodejs](https://plugins.jenkins.io/nodejs/) is a Jenkins plugin for Node.js that provides the NodeJS auto-installer, allowing to create as many NodeJS installations "profiles" as you want.

[Strapi](https://strapi.io/) is an open source Node.js Headless CMS to easily build customisable APIs.

[Standard](https://standardjs.com/) is a JavaScript Style Guide, with linter & automatic code fixer.

[React Starter Kit](https://www.reactstarterkit.com/) is an isomorphic web app boilerplate for web development built on top of [Node.js](https://nodejs.org/), [Express](http://expressjs.com/), [GraphQL](http://graphql.org/) and [React](https://facebook.github.io/react/), containing modern web development tools such as [Webpack](https://webpack.github.io/), [Babel](https://babeljs.io/) and [Browsersync](https://www.browsersync.io/). Helping you to stay productive following the best practices.

[Hexo](https://hexo.io/) is a A fast, simple & powerful blog framework, powered by Node.js.

# jQuery Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121087072-d0fb0400-c798-11eb-9398-5d9b71f98c47.png">
  <br />
</p>

## jQuery Learning Resources

[The OpenJS Foundation](https://openjsf.org/) is made up of 32 open source JavaScript projects including Appium, Dojo, Electron, jQuery, Node.js, and webpack. The foundation's mission is to support the healthy growth of JavaScript and web technologies by providing a neutral organization to host and sustain projects, as well as collaboratively fund activities that benefit the ecosystem as a whole.

[jQuery](https://jquery.com/) is a fast and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of web browsers.

[jQuery API Documentation](https://api.jquery.com/Jquery.ajax/)

[jQuery Learning Center](https://learn.jquery.com)

[Configuring JavaScript libraries in WebStorm](https://www.jetbrains.com/help/webstorm/configuring-javascript-libraries.html)

[JavaScript in Visual Studio Code](https://code.visualstudio.com/Docs/languages/javascript)

[JavaScript extensions for VS Code](https://code.visualstudio.com/docs/nodejs/extensions)

[jQuery Courses on Coursera](https://www.coursera.org/courses?query=jquery)

[jQuery Courses on Udemy](https://www.udemy.com/topic/jquery/)

[jQuery Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/jquery)

[Intro to jQuery on Udacity](https://www.udacity.com/course/intro-to-jquery--ud245)

[Intro to AJAX on Udacity ](https://www.udacity.com/course/intro-to-ajax--ud110)

[Learning jQuery on Codecademy](https://www.codecademy.com/learn/learn-jquery)

[jQuery Best Practices Training on Learning Tree](https://www.learningtree.com/courses/1610/jquery-best-practices-for-legacy-and-today/)

[Learning the jQuery Basics on Pluralsight](https://www.pluralsight.com/courses/code-school-try-jquery)

[jQuery In-Depth on Pluralsight](https://www.pluralsight.com/courses/jquery-in-depth)

[ASP.NET Ajax JavaScript and jQuery Course on Pluralsight](https://www.pluralsight.com/courses/aspdotnet-ajax-jscript)

[jQuery Certification from W3Schools](https://www.w3schools.com/cert/cert_jquery.asp)


## jQuery Tools, Libraries, and Frameworks

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[GraphQL](https://graphql.org/) is a query language for APIs and a runtime for fulfilling those queries with your existing data. It has support in Java, JavaScript, Ruby, Scala, and other programming languages.

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[Cheerio](https://github.com/cheeriojs/cheerio) is a fast, flexible, and lean implementation of core jQuery designed specifically for the server.

[jQuery UI](https://jqueryui.com/) is a curated set of user interface interactions, effects, widgets, and themes built on top of jQuery. Though, it should not be used in core code.

[jQuery Tools](https://github.com/jquerytools/jquerytools) is a collection of the most important user-interface components for modern websites. Used by large sites all over the world.

[Bridge.NET](https://bridge.net/) is an open source C#-to-JavaScript Compiler. Write your application in C# and run on billions of devices.

[Phantomas](https://www.npmjs.com/package/phantomas) is a [Headless Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md)-based web performance metrics collector and monitoring tool

[Featherlight](https://github.com/noelboss/featherlight) is a very lightweight jQuery lightbox plugin. It's simple yet flexible and easy to use.

# Electron Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/120394956-0b702700-c2e9-11eb-817d-872b002575b6.png">
  <br />
</p>


## Electron Learning Resources

[Electron](https://electronjs.org/) is a framework lets you write cross-platform desktop applications using JavaScript, HTML and CSS. It is based on [Node.js](https://nodejs.org/) and [Chromium](https://www.chromium.org/) and is used by the [Atom editor](https://github.com/atom/atom) and many other [apps](https://electronjs.org/apps).

[The OpenJS Foundation](https://openjsf.org/) is made up of 32 open source JavaScript projects including Appium, Dojo, Electron, jQuery, Node.js, and webpack. The foundation's mission is to support the healthy growth of JavaScript and web technologies by providing a neutral organization to host and sustain projects, as well as collaboratively fund activities that benefit the ecosystem as a whole.

[Electron Apps](https://www.electronjs.org/apps)

[Getting Started with Electron](https://www.electronjs.org/docs/tutorial/quick-start)

[Electron Development](https://www.electronjs.org/docs/development)

[Configuring JavaScript libraries in WebStorm](https://www.jetbrains.com/help/webstorm/configuring-javascript-libraries.html)

[JavaScript in Visual Studio Code](https://code.visualstudio.com/Docs/languages/javascript)

[JavaScript extensions for VS Code](https://code.visualstudio.com/docs/nodejs/extensions)

[Master Electron: Desktop Apps with HTML, JavaScript & CSS course on Udemy](https://www.udemy.com/course/master-electron/)

[Electron for Desktop Apps: The Complete Developer's Guide course on Udemy](https://www.udemy.com/course/electron-react-tutorial/)

[Electron From Scratch: Build Desktop Apps With JavaScript course on Udemy](https://www.udemy.com/course/electron-from-scratch/)

[Electron Courses on Coursera](https://www.coursera.org/courses?query=electron+js)

[Electron Fundamentals on Pluralsight](https://www.pluralsight.com/courses/electron-fundamentals)


## Electron Tools, Libraries, and Frameworks

[Electron Fiddle](https://electronjs.org/fiddle) is an application that lets you create and play with small Electron experiments. It greets you with a simple quick start template after opening. Simply choose the version of Electron you want to run with your project and then play around.

[Electron Builder](https://www.electron.build/) is a complete solution to package and build a ready for distribution Electron app with “auto update” support out of the box.

[Photon](https://github.com/connors/photon) is a UI toolkit for building desktop apps with Electron.

[Electron.NET](https://github.com/ElectronNET/Electron.NET) is an application that builds cross platform desktop apps with ASP.NET Core (Razor Pages, MVC, Blazor).

[Angular Electron](https://github.com/maximegris/angular-electron) is an application that bootstrap's and package's your project with Angular 11 and Electron 11 (Typescript + SASS + Hot Reload) for creating Desktop applications.

[Selenium](https://selenium.dev/) is a browser automation framework and ecosystem. Selenium specifically provides an infrastructure for the [W3C WebDriver specification](https://w3c.github.io/webdriver/) as a platform and language-neutral coding interface compatible with all major web browsers(Firefox, Google Chrome and Safari).

[Selenium IDE](https://selenium.dev/selenium-ide/) is an Open Source record and playback test automation for the web.

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code.

[GitHub Actions](https://docs.github.com/en/actions) will automate, customize, and execute your software development workflows right in your repository with GitHub Actions. You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.[GitHub Actions for Azure](https://docs.microsoft.com/en-us/azure/developer/github/github-actions) you can create workflows that you can set up in your repository to build, test, package, release and deploy to Azure.Learn more about all other integrations with Azure.

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[GraphQL](https://graphql.org/) is a query language for APIs and a runtime for fulfilling those queries with your existing data. It has support in Java, JavaScript, Ruby, Scala, and other programming languages.

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[Nest](https://nestjs.com/) is a framework for building efficient, scalable [Node.js](http://nodejs.org/) server-side applications. It uses modern JavaScript, is built with TypeScript (preserves compatibility with pure JavaScript) and combines elements of OOP (Object Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming).

[Quasar](https://quasar.dev/) is a framework that builds high-performance VueJS user interfaces in record time. Such as responsive Single Page Apps, SSR Apps, PWAs, Browser extensions, Hybrid Mobile Apps and Electron Apps.

[Gatsby](https://www.gatsbyjs.com/) is a free and open source framework based on React that helps developers build blazing fast websites and apps.

[React Starter Kit](https://www.reactstarterkit.com/) is an isomorphic web app boilerplate for web development built on top of [Node.js](https://nodejs.org/), [Express](http://expressjs.com/), [GraphQL](http://graphql.org/) and [React](https://facebook.github.io/react/), containing modern web development tools such as [Webpack](https://webpack.github.io/), [Babel](https://babeljs.io/) and [Browsersync](https://www.browsersync.io/). Helping you to stay productive following the best practices.

[Enzyme](https://github.com/enzymejs/enzyme) is a JavaScript Testing utility for React that makes it easier to test your React Components' output. The user can also manipulate, traverse, and in some ways simulate runtime given the output.

[Mocha](https://github.com/mochajs/mocha) is a simple, flexible, fun JavaScript test framework for Node.js & The Browser.

[Express](https://expressjs.com/) is a fast, unopinionated, minimalist web framework for node.

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavavScript.

[RxDB](https://github.com/pubkey/rxdb) is a NoSQL-database for JavaScript Applications like Websites, hybrid Apps, Electron-Apps, Progressive Web Apps and NodeJs.

[Redux](https://github.com/reduxjs/redux) is a predictable state container for JavaScript apps.

[Standard](https://standardjs.com/) is a JavaScript Style Guide, with linter & automatic code fixer.

[Lowdb](https://github.com/typicode/lowdb) is a small local JSON database powered by Lodash (supports Node, Electron and the browser).

[Nativefier](https://github.com/jiahaog/nativefier) is an application that lets you make any web page into a desktop electron application.

# C/C++ Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297894-961e0d80-a111-11eb-81c3-e2bd2ac9a7cd.png">
  <br />
</p>


## C/C++ Learning Resources

[C++](https://www.cplusplus.com/doc/tutorial/) is a cross-platform language that can be used to build high-performance applications developed by Bjarne Stroustrup, as an extension to the C language.

[C](https://www.iso.org/standard/74528.html) is a general-purpose, high-level language that was originally developed by Dennis M. Ritchie to develop the UNIX operating system at Bell Labs. It supports structured programming, lexical variable scope, and recursion, with a static type system. C also provides constructs that map efficiently to typical machine instructions, which makes it one was of the most widely used programming languages today.

[Embedded C](https://en.wikipedia.org/wiki/Embedded_C) is a set of language extensions for the C programming language by the [C Standards Committee](https://isocpp.org/std/the-committee) to address issues that exist between C extensions for different [embedded systems](https://en.wikipedia.org/wiki/Embedded_system). The extensions hep enhance microprocessor features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations. This makes Embedded C the most popular embedded software language in the world.

[C & C++ Developer Tools from JetBrains](https://www.jetbrains.com/cpp/)

[Open source C++ libraries on cppreference.com](https://en.cppreference.com/w/cpp/links/libs)

[C++ Graphics libraries](https://cpp.libhunt.com/libs/graphics)

[C++ Libraries in MATLAB](https://www.mathworks.com/help/matlab/call-cpp-library-functions.html)

[C++ Tools and Libraries Articles](https://www.cplusplus.com/articles/tools/)

[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

[Introduction C++ Education course on Google Developers](https://developers.google.com/edu/c++/)

[C++ style guide for Fuchsia](https://fuchsia.dev/fuchsia-src/development/languages/c-cpp/cpp-style)

[C and C++ Coding Style Guide by OpenTitan](https://docs.opentitan.org/doc/rm/c_cpp_coding_style/)

[Chromium C++ Style Guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/c++/c++.md)

[C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)

[C++ Style Guide for ROS](http://wiki.ros.org/CppStyleGuide)

[Learn C++](https://www.learncpp.com/)

[Learn C : An Interactive C Tutorial](https://www.learn-c.org/)

[C++ Institute](https://cppinstitute.org/free-c-and-c-courses)

[C++ Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/c-plus-plus)

[C++ Tutorials on W3Schools](https://www.w3schools.com/cpp/default.asp)

[Learn C Programming Online Courses on edX](https://www.edx.org/learn/c-programming)

[Learn C++ with Online Courses on edX](https://www.edx.org/learn/c-plus-plus)

[Learn C++ on Codecademy](https://www.codecademy.com/learn/learn-c-plus-plus)

[Coding for Everyone: C and C++ course on Coursera](https://www.coursera.org/specializations/coding-for-everyone)

[C++ For C Programmers on Coursera](https://www.coursera.org/learn/c-plus-plus-a)

[Top C Courses on Coursera](https://www.coursera.org/courses?query=c%20programming)

[C++ Online Courses on Udemy](https://www.udemy.com/topic/c-plus-plus/)

[Top C Courses on Udemy](https://www.udemy.com/topic/c-programming/)

[Basics of Embedded C Programming for Beginners on Udemy](https://www.udemy.com/course/embedded-c-programming-for-embedded-systems/)

[C++ For Programmers Course on Udacity](https://www.udacity.com/course/c-for-programmers--ud210)

[C++ Fundamentals Course on Pluralsight](https://www.pluralsight.com/courses/learn-program-cplusplus)

[Introduction to C++ on MIT Free Online Course Materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-096-introduction-to-c-january-iap-2011/)

[Introduction to C++ for Programmers | Harvard ](https://online-learning.harvard.edu/course/introduction-c-programmers)

[Online C Courses | Harvard University](https://online-learning.harvard.edu/subject/c)


## C/C++ Tools, Libraries, and Frameworks

[AWS SDK for C++](https://aws.amazon.com/sdk-for-cpp/)

[Azure SDK for C++](https://github.com/Azure/azure-sdk-for-cpp)

[Azure SDK for C](https://github.com/Azure/azure-sdk-for-c)

[C++ Client Libraries for Google Cloud Services](https://github.com/googleapis/google-cloud-cpp)

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Vcpkg](https://github.com/microsoft/vcpkg) is a C++ Library Manager for Windows, Linux, and MacOS.

[ReSharper C++](https://www.jetbrains.com/resharper-cpp/features/) is a Visual Studio Extension for C++ developers developed by JetBrains.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages. All code inspections are run on the fly.

[CLion](https://www.jetbrains.com/clion/features/) is a cross-platform IDE for C and C++ developers developed by JetBrains.

[Code::Blocks](https://www.codeblocks.org/) is a free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable. Built around a plugin framework, Code::Blocks can be extended with plugins.

[CppSharp](https://github.com/mono/CppSharp) is a tool and set of libraries which facilitates the usage of native C/C++ code with the .NET ecosystem. It consumes C/C++ header and library files and generates the necessary glue code to surface the native API as a managed API. Such an API can be used to consume an existing native library in your managed code or add managed scripting support to a native codebase.

[Conan](https://conan.io/) is an Open Source Package Manager for C++ development and dependency management into the 21st century and on par with the other development ecosystems.

[High Performance Computing (HPC) SDK](https://developer.nvidia.com/hpc) is a comprehensive toolbox for GPU accelerating HPC modeling and simulation applications. It includes the C, C++, and Fortran compilers, libraries, and analysis tools necessary for developing HPC applications on the NVIDIA platform.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs. Interoperability with established technologies such as CUDA, TBB, and OpenMP integrates with existing software.

[Boost](https://www.boost.org/) is an educational opportunity focused on cutting-edge C++. Boost has been a participant in the annual Google Summer of Code since 2007, in which students develop their skills by working on Boost Library development.

[Automake](https://www.gnu.org/software/automake/) is a tool for automatically generating Makefile.in files compliant with the GNU Coding Standards. Automake requires the use of GNU Autoconf.

[Cmake](https://cmake.org/) is an open-source, cross-platform family of tools designed to build, test and package software. CMake is used to control the software compilation process using simple platform and compiler independent configuration files, and generate native makefiles and workspaces that can be used in the compiler environment of your choice.

[GDB](http://www.gnu.org/software/gdb/) is a debugger, that allows you to see what is going on `inside' another program while it executes or what another program was doing at the moment it crashed.

[GCC](https://gcc.gnu.org/) is a compiler Collection that includes front ends for C, C++, Objective-C, Fortran, Ada, Go, and D, as well as libraries for these languages.

[GSL](https://www.gnu.org/software/gsl/) is a numerical library for C and C++ programmers. It is free software under the GNU General Public License. The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. There are over 1000 functions in total with an extensive test suite.

[OpenGL Extension Wrangler Library (GLEW)](https://www.opengl.org/sdk/libs/GLEW/) is a cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform.

[Libtool](https://www.gnu.org/software/libtool/) is a generic library support script that hides the complexity of using shared libraries behind a consistent, portable interface. To use Libtool, add the new generic library building commands to your Makefile, Makefile.in, or Makefile.am.

[Maven](https://maven.apache.org/) is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

[TAU (Tuning And Analysis Utilities)](http://www.cs.uoregon.edu/research/tau/home.php) is capable of gathering performance information through instrumentation of functions, methods, basic blocks, and statements as well as event-based sampling. All C++ language features are supported including templates and namespaces.

[Clang](https://clang.llvm.org/) is a production quality C, Objective-C, C++ and Objective-C++ compiler when targeting X86-32, X86-64, and ARM (other targets may have caveats, but are usually easy to fix). Clang is used in production to build performance-critical software like Google Chrome or Firefox.

[OpenCV](https://opencv.org/) is a highly optimized library with focus on real-time applications. Cross-Platform C++, Python and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Libcu++](https://nvidia.github.io/libcudacxx) is the NVIDIA C++ Standard Library for your entire system. It provides a heterogeneous implementation of the C++ Standard Library that can be used in and between CPU and GPU code.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[Oat++](https://oatpp.io/) is a light and powerful C++ web framework for highly scalable and resource-efficient web application. It's zero-dependency and easy-portable.

[JavaCPP](https://github.com/bytedeco/javacpp) is a program that provides efficient access to native C++ inside Java, not unlike the way some C/C++ compilers interact with assembly language.

[Cython](https://cython.org/) is a language that makes writing C extensions for Python as easy as Python itself. Cython is based on Pyrex, but supports more cutting edge functionality and optimizations such as calling C functions and declaring C types on variables and class attributes.

[Spdlog](https://github.com/gabime/spdlog) is a very fast, header-only/compiled, C++ logging library.

[Infer](https://fbinfer.com/) is a static analysis tool for Java, C++, Objective-C, and C. Infer is written in [OCaml](https://ocaml.org/).

# Java Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93925952-c0b6fd80-fccb-11ea-9f90-21c4148e3c86.png">
  <br />
</p>

## Java Learning Resources

[Java](https://www.oracle.com/java/) is a popular programming language and development platform(JDK). It reduces costs, shortens development timeframes, drives innovation, and improves application services. With millions of developers running more than 51 billion Java Virtual Machines worldwide.

[The Eclipse Foundation](https://www.eclipse.org/downloads/) is home to a worldwide community of developers, the Eclipse IDE, Jakarta EE and over 375 open source projects, including runtimes, tools and frameworks for Java and other languages.

[Getting Started with Java](https://docs.oracle.com/javase/tutorial/)

[Oracle Java certifications from Oracle University](https://education.oracle.com/java-certification-benefits)

[Google Developers Training](https://developers.google.com/training/)

[Google Developers Certification](https://developers.google.com/certification/)

[Java Tutorial by W3Schools](https://www.w3schools.com/java/)

[Building Your First Android App in Java](codelabs.developers.google.com/codelabs/build-your-first-android-app/)

[Getting Started with Java in Visual Studio Code](https://code.visualstudio.com/docs/java/java-tutorial)

[Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)

[AOSP Java Code Style for Contributors](https://source.android.com/setup/contribute/code-style)

[Chromium Java style guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/java/java.md)

[Get Started with OR-Tools for Java](https://developers.google.com/optimization/introduction/java)

[Getting started with Java Tool Installer task for Azure Pipelines](https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/tool/java-tool-installer)

[Gradle User Manual](https://docs.gradle.org/current/userguide/userguide.html)

## Java Tools and Frameworks

[Java SE](https://www.oracle.com/java/technologies/javase/tools-jsp.html) contains several tools to assist in program development and debugging, and in the monitoring and troubleshooting of production applications.

[JDK Development Tools](https://docs.oracle.com/javase/7/docs/technotes/tools/) includes the Java Web Start Tools (javaws) Java Troubleshooting, Profiling, Monitoring and Management Tools (jcmd, jconsole, jmc, jvisualvm); and Java Web Services Tools (schemagen, wsgen, wsimport, xjc).

[Android Studio](https://developer.android.com/studio/) is the official integrated development environment for Google's Android operating system, built on JetBrains' IntelliJ IDEA software and designed specifically for Android development. Availble on Windows, macOS, Linux, Chrome OS.

[IntelliJ IDEA](https://www.jetbrains.com/idea/) is an IDE for Java, but it also understands and provides intelligent coding assistance for a large variety of other languages such as Kotlin, SQL, JPQL, HTML, JavaScript, etc., even if the language expression is injected into a String literal in your Java code.

[NetBeans](https://netbeans.org/features/java/index.html) is an IDE provides Java developers with all the tools needed to create professional desktop, mobile and enterprise applications. Creating, Editing, and Refactoring. The IDE provides wizards and templates to let you create Java EE, Java SE, and Java ME applications.

[Java Design Patterns ](https://github.com/iluwatar/java-design-patterns) is a collection of the best formalized practices a programmer can use to solve common problems when designing an application or system.

[Elasticsearch](https://www.elastic.co/products/elasticsearch) is a distributed RESTful search engine built for the cloud written in Java.

[RxJava](https://github.com/ReactiveX/RxJava) is a Java VM implementation of [Reactive Extensions](http://reactivex.io/): a library for composing asynchronous and event-based programs by using observable sequences. It extends the [observer pattern](http://en.wikipedia.org/wiki/Observer_pattern) to support sequences of data/events and adds operators that allow you to compose sequences together declaratively while abstracting away concerns about things like low-level threading, synchronization, thread-safety and concurrent data structures.

[Guava](https://github.com/google/guava) is a set of core Java libraries from Google that includes new collection types (such as multimap and multiset), immutable collections, a graph library, and utilities for concurrency, I/O, hashing, caching, primitives, strings, and more! It is widely used on most Java projects within Google, and widely used by many other companies as well.

[okhttp](https://square.github.io/okhttp/) is a HTTP client for Java and Kotlin developed by Square.

[Retrofit](https://square.github.io/retrofit/) is a type-safe HTTP client for Android and Java develped by Square.

[LeakCanary](https://square.github.io/leakcanary/) is a memory leak detection library for Android develped by Square.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for large-scale data processing. It provides high-level APIs in Scala, Java, Python, and R, and an optimized engine that supports general computation graphs for data analysis. It also supports a rich set of higher-level tools including Spark SQL for SQL and DataFrames, MLlib for machine learning, GraphX for graph processing, and Structured Streaming for stream processing.

[Apache Flink](https://flink.apache.org/) is an open source stream processing framework with powerful stream- and batch-processing capabilities with elegant and fluent APIs in Java and Scala.

[Fastjson](https://github.com/alibaba/fastjson/wiki) is a Java library that can be used to convert Java Objects into their JSON representation. It can also be used to convert a JSON string to an equivalent Java object.

[libGDX](https://libgdx.com/) is a cross-platform Java game development framework based on OpenGL (ES) that works on Windows, Linux, Mac OS X, Android, your WebGL enabled browser and iOS.

[Jenkins](https://www.jenkins.io/) is the leading open-source automation server. Built with Java, it provides over 1700 [plugins](https://plugins.jenkins.io/) to support automating virtually anything, so that humans can actually spend their time doing things machines cannot.

[DBeaver](https://dbeaver.io/) is a free multi-platform database tool for developers, SQL programmers, database administrators and analysts. Supports any database which has JDBC driver (which basically means - ANY database). EE version also supports non-JDBC datasources (MongoDB, Cassandra, Redis, DynamoDB, etc).

[Redisson](https://redisson.pro/) is a Redis Java client with features of In-Memory Data Grid. Over 50 Redis based Java objects and services: Set, Multimap, SortedSet, Map, List, Queue, Deque, Semaphore, Lock, AtomicLong, Map Reduce, Publish / Subscribe, Bloom filter, Spring Cache, Tomcat, Scheduler, JCache API, Hibernate, MyBatis, RPC, and local cache.

[GraalVM](https://www.graalvm.org/) is a universal virtual machine for running applications written in JavaScript, Python, Ruby, R, JVM-based languages like Java, Scala, Clojure, Kotlin, and LLVM-based languages such as C and C++.

[Gradle](https://gradle.org/) is a build automation tool for multi-language software development. From mobile apps to microservices, from small startups to big enterprises, Gradle helps teams build, automate and deliver better software, faster. Write in Java, C++, Python or your language of choice.

[Apache Groovy](http://www.groovy-lang.org/) is a powerful, optionally typed and dynamic language, with static-typing and static compilation capabilities, for the Java platform aimed at improving developer productivity thanks to a concise, familiar and easy to learn syntax. It integrates smoothly with any Java program, and immediately delivers to your application powerful features, including scripting capabilities, Domain-Specific Language authoring, runtime and compile-time meta-programming and functional programming.

[JaCoCo](https://www.jacoco.org/jacoco/) is a free code coverage library for Java, which has been created by the EclEmma team based on the lessons learned from using and integration existing libraries for many years.

[Apache JMeter](http://jmeter.apache.org/) is  used to test performance both on static and dynamic resources, Web dynamic applications. It also used to simulate a heavy load on a server, group of servers, network or object to test its strength or to analyze overall performance under different load types.

[Junit](https://junit.org/) is a simple framework to write repeatable tests. It is an instance of the xUnit architecture for unit testing frameworks.

[Mockito](https://site.mockito.org/) is the most popular Mocking framework for unit tests written in Java.

[SpotBugs](https://spotbugs.github.io/) is a program which uses static analysis to look for bugs in Java code.

[SpringBoot](https://spring.io/projects/spring-boot) is a great tool that helps you to create Spring-powered, production-grade applications and services with absolute minimum fuss. It takes an opinionated view of the Spring platform so that new and existing users can quickly get to the bits they need.

[YourKit](https://www.yourkit.com/) is a technology leader, creator of the most innovative and intelligent tools for profiling Java & .NET applications.

# Kotlin Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93389835-9a074b80-f821-11ea-8c6c-746a5d99b1a5.png">
  <br />
</p>

## Kotlin Learning Resources

[Kotlin](https://kotlinlang.org/) is a very popular programming language that targets the JVM. Kotlin has experienced a surge in popularity the last few years making it the most popular JVM language not including Java.

[Kotlin Programming Language Reference](https://kotlinlang.org/docs/reference/)

[Google Developers Training](https://developers.google.com/training/)

[Google Developers Certification](https://developers.google.com/certification/)

[Kotlin style guide](https://developer.android.com/kotlin/style-guide)

[Learn the Kotlin programming language](https://developer.android.com/kotlin/learn)

[Get Started with Kotlin on Android](https://developer.android.com/kotlin/get-started)

[Kotlin for cross-platform mobile development](https://kotlinlang.org/lp/mobile/)

[Using Kotlin with Quakus](https://quarkus.io/guides/kotlin)

[Building web applications with Spring Boot and Kotlin](https://spring.io/guides/tutorials/spring-boot-kotlin/)

[Migrating build logic from Groovy to Kotlin](https://guides.gradle.org/migrating-build-logic-from-groovy-to-kotlin/)

[Kotlin Playground: Edit, Run, Share Kotlin Code Online](https://play.kotlinlang.org/)

[An Absolute Beginner's Guide to Kotlin by Treehouse](https://blog.teamtreehouse.com/absolute-beginners-guide-kotlin)

[Kotlin Courses Online from Udemy](https://www.udemy.com/topic/kotlin/)

[Learning Kotlin from Codecademy](https://www.codecademy.com/learn/learn-kotlin)

[Kotlin Bootcamp for Programmers course from Udacity](https://www.udacity.com/course/kotlin-bootcamp-for-programmers--ud9011)

## Kotlin Tools, Libraries, and Frameworks

[Android Studio](https://developer.android.com/studio/) is the official integrated development environment for Google's Android operating system, built on JetBrains' IntelliJ IDEA software and designed specifically for Android development. Available on Windows, macOS, Linux, and Chrome OS.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108637349-29530380-743f-11eb-8c61-549064b7d80b.png">
</p>

[Android Virtual Device (AVD)](https://developer.android.com/studio/run/managing-avds) is a configuration in [Android Studio](https://developer.android.com/studio/intro) that defines the characteristics of an Android phone, tablet, Wear OS, Android TV, or Automotive OS device that you want to simulate in the Android Emulator. The [Android Emulator](https://developer.android.com/studio/run/emulator) simulates Android devices on your computer so that you can test your application on a variety of devices and Android API levels without needing to have each physical device.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108637365-2c4df400-743f-11eb-8265-c07faab3523f.png">
</p>

[IntelliJ IDEA](https://www.jetbrains.com/idea/) is an IDE for Java, but it also understands and provides intelligent coding assistance for a large variety of other languages such as Kotlin, SQL, JPQL, HTML, JavaScript, etc., even if the language expression is injected into a String literal in your Java code.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[Gradle](https://github.com/gradle/gradle) is a build automation tool that supports multi-language development. If you're building, testing, publishing, and deploying software on any platform, Gradle offers a flexible model that can support the entire development lifecycle from compiling and packaging code to publishing web sites. Gradle is designed to support build automation across multiple languages and platforms including Java, Scala, Android, C/C++, Swift, and Groovy, which is closely integrated with development tools and continuous integration servers including Eclipse, IntelliJ, and Jenkins.

[Kotlin Xcode compatibility Gradle plugin](https://github.com/Kotlin/xcode-compat) is a plugin is used by [AppCode](https://jetbrains.com/appcode) to set up Kotlin/Native project along with Xcode.

[Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) is the AI code completion tool trusted by millions of developers to code faster with fewer errors. Whether you are a new dev or a seasoned pro, working solo or part of a team, Tabnine will help push your productivity to new heights while cutting your QA time.

[Okhttp](https://square.github.io/okhttp/) is a HTTP client for Java and Kotlin developed by Square.

[Vue-kotlin](https://github.com/nosix/vue-kotlin) is a collection of libraries and tools supporting the use of Vue.js in Kotlin.

[Kotlinx-lincheck](https://github.com/Kotlin/kotlinx-lincheck) is a framework for testing concurrent data structures for correctness.

[Kotlinx-io](https://github.com/Kotlin/kotlinx-io) is a multiplatform library for processing binary data, working with memory blocks, interacting with the platform, and performing other low level operations.

[Kotlinx-knit](https://github.com/Kotlin/kotlinx-knit) is a tool that produces Kotlin source example files and tests from markdown documents with embedded snippets of Kotlin code. It also helps to add links to the API documentation website into the documents and has a few other helpful markdown-management features.

# Scala Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/95688293-09bcec00-0bbe-11eb-8d0d-d75706856673.png">
  <br />
</p>

## Scala Learning Resources

[Scala](https://scala-lang.org/) is a combination of object-oriented and functional programming in one concise, high-level language. Scala's static types help avoid bugs in complex applications, and its JVM and JavaScript runtimes let you build high-performance systems with easy access to huge ecosystems of libraries.

[Scala Style Guide](https://docs.scala-lang.org/style/)

[Databricks Scala Style Guide](https://github.com/databricks/scala-style-guide)

[Data Science using Scala and Spark on Azure](https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/scala-walkthrough)

[Creating a Scala Maven application for Apache Spark in HDInsight using IntelliJ](https://docs.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-create-standalone-application)

[Intro to Spark DataFrames using Scala with Azure Databricks](https://docs.microsoft.com/en-us/azure/databricks/spark/latest/dataframes-datasets/introduction-to-dataframes-scala)

[Using Scala to Program AWS Glue ETL Scripts](https://docs.aws.amazon.com/glue/latest/dg/glue-etl-scala-using.html)

[Using Flink Scala shell with Amazon EMR clusters](https://docs.aws.amazon.com/emr/latest/ReleaseGuide/flink-scala.html)

[AWS EMR and Spark 2 using Scala from Udemy](https://www.udemy.com/course/aws-emr-and-spark-2-using-scala/)

[Using the Google Cloud Storage connector with Apache Spark](https://cloud.google.com/dataproc/docs/tutorials/gcs-connector-spark-tutorial)

[Write and run Spark Scala jobs on Cloud Dataproc for Google Cloud](https://cloud.google.com/dataproc/docs/tutorials/spark-scala)

[Scala Courses and Certifications from edX](https://www.edx.org/learn/scala)

[Scala Courses from Coursera](https://www.coursera.org/courses?query=scala)

[Top Scala Courses from Udemy](https://www.udemy.com/topic/scala/)

## Scala Tools, Libraries, and Frameworks

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[Scala Syntax (official)](https://marketplace.visualstudio.com/items?itemName=scala-lang.scala) is an extension for Visual Studio Code that provides syntax highlighting for Scala 2 and Scala 3 source files.

[ScalaScript](https://marketplace.visualstudio.com/items?itemName=peter-cherna.scalascript) is an extension for Visual Studio Code that provides provides for [Scala Inc](https://www.scala.com/) ScalaScript digital signage scripting language.

[Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) is the AI code completion tool trusted by millions of developers to code faster with fewer errors. Whether you are a new dev or a seasoned pro, working solo or part of a team, Tabnine will help push your productivity to new heights while cutting your QA time.

[IntelliJ IDEA Scala plugin](https://plugins.jetbrains.com/plugin/1347-scala) is a tool that extends IntelliJ IDEA’s toolset with support for Scala, SBT, Scala.js, Hocon, and Play Framework. Support for Scala, SBT and Hocon is available for free in IntelliJ IDEA Community Edition, while support for Play Framework and Scala.js is available only in IntelliJ IDEA Ultimate.

[ScalaTest™](https://www.scalatest.org) is the most flexible and most popular testing tool in the Scala ecosystem. With ScalaTest, you can test Scala, Scala.js (JavaScript), Scala Native, Dotty (Scala 3), and Java code. It offers deep integration with tools such as JUnit, TestNG, Ant, Maven, sbt, ScalaCheck, JMock, EasyMock, Mockito, ScalaMock, Selenium, Eclipse, NetBeans, and IntelliJ, ScalaTest makes it easy to take your testing to a higher, more productive level in new or existing Scala, Scala.js, or Java projects.

[Dotty](https://github.com/lampepfl/dotty) is a platform to try out new language concepts and compiler technologies for Scala where the focus is mainly on simplification. It removes extraneous syntax (e.g. no XML literals), and try to boil down Scala's types into a smaller set of more fundamental constructors.

[Metals](https://github.com/scalameta/metals) is a Scala language server with rich IDE features.

[WartRemover](https://github.com/wartremover/wartremover) is a flexible Scala code linting tool.

[Mill](https://github.com/com-lihaoyi/mill) is a shiny new Java/Scala build tool that removes the complexity that you may have with Maven or Gradle.

[Bloop](https://github.com/scalacenter/bloop) is a build server and CLI tool to compile, test and run Scala fast from any editor or build tool.

[ScalaMock](https://scalamock.org/) is a native Scala mocking framework. It uses macros to create mocks allowing the macros and compile-time reflection to create type safe code or manipulate programs.

[Scapegoat](https://github.com/scapegoat-scala/scapegoat) is a Scala static code analyzer, what is more colloquially known as a code lint tool or linter. Scapegoat works in a similar vein to Java's [FindBugs](http://findbugs.sourceforge.net/) or [checkstyle](http://checkstyle.sourceforge.net/), or [Scala's Scalastyle](https://github.com/scalastyle/scalastyle).

[AWScala](https://github.com/seratch/AWScala) is a tool that enables Scala developers to easily work with Amazon Web Services in the Scala way.

[Scala.js](https://www.scala-js.org/) is a compiler that converts Scala to JavaScript.

[Polynote](https://polynote.org/) is an experimental polyglot notebook environment. Currently, it supports Scala and Python (with or without Spark), SQL, and Vega.

[Scala Native](http://scala-native.org/) is an optimizing ahead-of-time compiler and lightweight managed runtime designed specifically for Scala.

[Gitbucket](https://gitbucket.github.io/) is a Git platform powered by Scala with easy installation, high extensibility & GitHub API compatibility.

[Finagle](https://twitter.github.io/finagle) is a fault tolerant, protocol-agnostic RPC system

[Gatling](https://gatling.io/) is a load test tool. It officially supports HTTP, WebSocket, Server-Sent-Events and JMS.

[Scalatra](https://scalatra.org/) is a tiny Scala high-performance, async web framework, inspired by [Sinatra](https://www.sinatrarb.com/).

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for large-scale data processing. It provides high-level APIs in Scala, Java, Python, and R, and an optimized engine that supports general computation graphs for data analysis. It also supports a rich set of higher-level tools including Spark SQL for SQL and DataFrames, MLlib for machine learning, GraphX for graph processing, and Structured Streaming for stream processing.

[Apache Spark Connector for SQL Server and Azure SQL](https://github.com/microsoft/sql-spark-connector) is a high-performance connector that enables you to use transactional data in big data analytics and persists results for ad-hoc queries or reporting. The connector allows you to use any SQL database, on-premises or in the cloud, as an input data source or output data sink for Spark jobs.

[Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) is a fast and collaborative Apache Spark-based big data analytics service designed for data science and data engineering. Azure Databricks, sets up your Apache Spark environment in minutes, autoscale, and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

[Apache PredictionIO](https://predictionio.apache.org/) is an open source machine learning framework for developers, data scientists, and end users. It supports event collection, deployment of algorithms, evaluation, querying predictive results via REST APIs. It is based on scalable open source services like Hadoop, HBase (and other DBs), Elasticsearch, Spark and implements what is called a Lambda Architecture.

[Cluster Manager for Apache Kafka(CMAK)](https://github.com/yahoo/CMAK) is a tool for managing [Apache Kafka](https://kafka.apache.org/) clusters.

[BigDL](https://bigdl-project.github.io/) is a distributed deep learning library for Apache Spark. With BigDL, users can write their deep learning applications as standard Spark programs, which can directly run on top of existing Spark or Hadoop clusters.

[Eclipse Deeplearning4J (DL4J)](https://deeplearning4j.konduit.ai/) is a set of projects intended to support all the needs of a JVM-based(Scala, Kotlin, Clojure, and Groovy) deep learning application. This means starting with the raw data, loading and preprocessing it from wherever and whatever format it is in to building and tuning a wide variety of simple and complex deep learning networks.

[Play Framework](https://github.com/playframework/playframework) is a web framework combines productivity and performance making it easy to build scalable web applications with Java and Scala.

# Clojure Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/99859408-d23e4980-2b44-11eb-863d-9fb617c9999f.png">
  <br />
</p>

## Clojure Learning Resources

[Clojure](https://clojure.org/) is a dynamic, general-purpose programming language, combining the approachability and interactive development of a scripting language with an efficient and robust infrastructure for multithreaded programming.

[ClojureScript](https://clojurescript.org/) is a compiler for Clojure that targets JavaScript. It is designed to emit JavaScript code which is compatible with the advanced compilation mode of the Google Closure optimizing compiler.

[Clojure Community Resources](https://clojure.org/community/resources)

[Clojure Training](https://www.clojure.org/community/training)

[Learning Clojure on Udemy](https://www.udemy.com/course/learning-clojure/)

[Clojure Fundamentals on Pluralsight](https://www.pluralsight.com/courses/clojure-fundamentals-part-one)

[Web Development in Clojure](https://purelyfunctional.tv/browse/)

[Clojure Online Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/clojure)

[Clojure Workshop on Packt](https://www.packtpub.com/product/the-clojure-workshop/9781838825485)

[Clojure Style Guide](https://guide.clojure.style)

## Clojure Tools, Libraries, and Frameworks

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[clojureVSCode](https://github.com/avli/clojureVSCode) is an extension that provides Clojure and ClojureScript support for Visual Studio Code.

[Reagent](https://github.com/reagent-project/reagent) is a minimalistic [ClojureScript](https://github.com/clojure/clojurescript) interface to [React](https://facebook.github.io/react/).

[Calva](https://marketplace.visualstudio.com/items?itemName=betterthantomorrow.calva) is  an integrated REPL powered environment for enjoyable and productive [Clojure](https://clojure.org/) and [ClojureScript](https://clojurescript.org/) in [Visual Studio Code](https://code.visualstudio.com/). It includes inline code evaluation, [Paredit](https://calva.io/paredit/), a Clojure formatter, a test runner, Clojure syntax highlighting, and more. Most of the REPL power is harvested from the produce of [The Orchard](https://github.com/clojure-emacs/orchard).

[Cursive](https://cursive-ide.com/index.html) is a Clojure(Script) IDE with advanced structural editing, refactorings, VCS integration and much more, all out of the box.

[Clj and deps.edn](https://clojure.org/guides/deps_and_cli) is a tool for managing dependencies, running a REPL, and executing Clojure programs, built by the Clojure core team.

[Leiningen](https://leiningen.org/) is an extensible build tool that provides dependency management, REPL support, testing, packaging, deployment, and many other capabilities.

[Boot](https://github.com/boot-clj/boot) is a Clojure build framework and ad-hoc Clojure script evaluator. Boot provides a runtime environment that includes all of the tools needed to build Clojure projects from scripts written in Clojure.

[Clojars](https://clojars.org/) is a Clojure-focused Maven repository.

[Clojure Toolbox](https://www.clojure-toolbox.com/) is  a categorized index of Clojure libraries.

[Vim Firepalce](https://github.com/tpope/vim-fireplace) is a plugin in Vim that adds support for [Clojure](https://clojure.org/) and [ClojureScript](https://clojurescript.org/).

[CIDER](https://cider.mx/) is a plugin extends Emacs with support for interactive programming in Clojure. The features are centered around cider-mode, an Emacs minor-mode that complements clojure-mode project.

[Clojure-mode](https://github.com/clojure-emacs/clojure-mode) is a Emacs major mode that provides font-lock (syntax highlighting), indentation, navigation and refactoring support for the Clojure(Script).

[Inf-clojure](https://github.com/clojure-emacs/inf-clojure) is a package that provides basic interaction with a Clojure subprocess (REPL), based on ideas from the popular inferior-lisp package.

[Riemann](https://riemann.io/) is a network event stream processing system for monitoring distributed systems, in Clojure.

[Datascript](https://github.com/tonsky/datascript) is an immutable in-memory database and Datalog query engine in Clojure, ClojureScript, and JavaScript.

[Compojure](https://github.com/weavejester/compojure) is a small routing library for [Ring](https://github.com/ring-clojure/ring) that allows web applications to be composed of small, independent parts.

[Ring](https://github.com/ring-clojure/ring) is a Clojure web applications library inspired by Python's WSGI and Ruby's Rack. By abstracting the details of HTTP into a simple, unified API, Ring allows web applications to be constructed of modular components that can be shared among a variety of applications, web servers, and web frameworks.

[Hiccup](https://github.com/weavejester/hiccup) is a library for representing HTML in Clojure. It uses vectors to represent elements, and maps to represent an element's attributes.

[Onyx](https://github.com/onyx-platform/onyx) is a distributed, masterless, high performance, fault tolerant data processing system.

[Lumo ](https://github.com/anmonteiro/lumo) is a standalone ClojureScript environment that runs on Node.js and the V8 JavaScript engine. It provides out-of-the-box access to the entire Node.js ecosystem, including a ClojureScript REPL.

[Arcadia](https://github.com/arcadia-unity/Arcadia) is an integration of the Clojure Programming Language with the Unity 3D game engine.

[Lacinia](https://lacinia.readthedocs.io/en/latest/) is a full GraphQL implementation in pure Clojure.

# Python Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93133273-ce490380-f68b-11ea-81d0-7f6a3debe6c0.png">
  <br />

</p>

## Python Learning Resources

[Python](https://www.python.org) is an interpreted, high-level programming language. Python is used heavily in the fields of Data Science and Machine Learning.

[Python Developer’s Guide](https://devguide.python.org) is a comprehensive resource for contributing to Python – for both new and experienced contributors. It is maintained by the same community that maintains Python.

[Azure Functions Python developer guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference-python) is an introduction to developing Azure Functions using Python. The content below assumes that you've already read the [Azure Functions developers guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference).

[CheckiO](https://checkio.org/) is a programming learning platform and a gamified website that teaches Python through solving code challenges and competing for the most elegant and creative solutions.

[Python Institute](https://pythoninstitute.org)

[PCEP – Certified Entry-Level Python Programmer certification](https://pythoninstitute.org/pcep-certification-entry-level/)

[PCAP – Certified Associate in Python Programming certification](https://pythoninstitute.org/pcap-certification-associate/)

[PCPP – Certified Professional in Python Programming 1 certification](https://pythoninstitute.org/pcpp-certification-professional/)

[PCPP – Certified Professional in Python Programming 2](https://pythoninstitute.org/pcpp-certification-professional/)

[MTA: Introduction to Programming Using Python Certification](https://docs.microsoft.com/en-us/learn/certifications/mta-introduction-to-programming-using-python)

[Getting Started with Python in Visual Studio Code](https://code.visualstudio.com/docs/python/python-tutorial)

[Google's Python Style Guide](https://google.github.io/styleguide/pyguide.html)

[Google's Python Education Class](https://developers.google.com/edu/python/)

[Real Python](https://realpython.com)

[The Python Open Source Computer Science Degree by Forrest Knight](https://github.com/ForrestKnight/open-source-cs-python)

[Intro to Python for Data Science](https://www.datacamp.com/courses/intro-to-python-for-data-science)

[Intro to Python by W3schools](https://www.w3schools.com/python/python_intro.asp)

[Codecademy's Python 3 course](https://www.codecademy.com/learn/learn-python-3)

[Learn Python with Online Courses and Classes from edX](https://www.edx.org/learn/python)

[Python Courses Online from Coursera](https://www.coursera.org/courses?query=python)

# Python Frameworks, Libraries, and Tools

[Python Package Index (PyPI)](https://pypi.org/) is a repository of software for the Python programming language. PyPI helps you find and install software developed and shared by the Python community.

[PyCharm](https://www.jetbrains.com/pycharm/) is the best IDE I've ever used. With PyCharm, you can access the command line, connect to a database, create a virtual environment, and manage your version control system all in one place, saving time by avoiding constantly switching between windows.

[Python Tools for Visual Studio(PTVS)](https://microsoft.github.io/PTVS/) is a free, open source plugin that turns Visual Studio into a Python IDE. It supports editing, browsing, IntelliSense, mixed Python/C++ debugging, remote Linux/MacOS debugging, profiling, IPython, and web development with Django and other frameworks.

[Django](https://www.djangoproject.com/) is a high-level Python Web framework that encourages rapid development and clean, pragmatic design.

[Flask](https://flask.palletsprojects.com/) is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries.

[Web2py](http://web2py.com/) is an open-source web application framework written in Python allowing allows web developers to program dynamic web content. One web2py instance can run multiple web sites using different databases.

[AWS Chalice](https://github.com/aws/chalice) is a framework for writing serverless apps in python. It allows you to quickly create and deploy applications that use AWS Lambda.

[Tornado](https://www.tornadoweb.org/) is a Python web framework and asynchronous networking library. Tornado uses a non-blocking network I/O, which can scale to tens of thousands of open connections.

[HTTPie](https://github.com/httpie/httpie) is a command line HTTP client that makes CLI interaction with web services as easy as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers.

[Scrapy](https://scrapy.org/) is a fast high-level web crawling and web scraping framework, used to crawl websites and extract structured data from their pages. It can be used for a wide range of purposes, from data mining to monitoring and automated testing.

[Sentry](https://sentry.io/) is a service that helps you monitor and fix crashes in realtime. The server is in Python, but it contains a full API for sending events from any language, in any application.

[Pipenv](https://github.com/pypa/pipenv) is a tool that aims to bring the best of all packaging worlds (bundler, composer, npm, cargo, yarn, etc.) to the Python world.

[Python Fire](https://github.com/google/python-fire) is a library for automatically generating command line interfaces (CLIs) from absolutely any Python object.

[Bottle](https://github.com/bottlepy/bottle) is a fast, simple and lightweight [WSGI](https://www.wsgi.org/) micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the [Python Standard Library](https://docs.python.org/library/).

[CherryPy](https://cherrypy.org) is a minimalist Python object-oriented HTTP web framework.

[Sanic](https://github.com/huge-success/sanic) is a Python 3.6+ web server and web framework that's written to go fast.

[Pyramid](https://trypyramid.com) is a small and fast open source Python web framework. It makes real-world web application development and deployment more fun and more productive.

[TurboGears](https://turbogears.org) is a hybrid web framework able to act both as a Full Stack framework or as a Microframework.

[Falcon](https://falconframework.org/) is a reliable, high-performance Python web framework for building large-scale app backends and microservices with support for MongoDB, Pluggable Applications and autogenerated Admin.

[Neural Network Intelligence(NNI)](https://github.com/microsoft/nni) is an open source AutoML toolkit for automate machine learning lifecycle, including [Feature Engineering](https://github.com/microsoft/nni/blob/master/docs/en_US/FeatureEngineering/Overview.md), [Neural Architecture Search](https://github.com/microsoft/nni/blob/master/docs/en_US/NAS/Overview.md), [Model Compression](https://github.com/microsoft/nni/blob/master/docs/en_US/Compressor/Overview.md) and [Hyperparameter Tuning](https://github.com/microsoft/nni/blob/master/docs/en_US/Tuner/BuiltinTuner.md).

[Dash](https://plotly.com/dash) is a popular Python framework for building ML & data science web apps for Python, R, Julia, and Jupyter.

[Luigi](https://github.com/spotify/luigi) is a Python module that helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization etc. It also comes with Hadoop support built-in.

[Locust](https://github.com/locustio/locust) is an easy to use, scriptable and scalable performance testing tool.

[spaCy](https://github.com/explosion/spaCy) is a library for advanced Natural Language Processing in Python and Cython.

[NumPy](https://www.numpy.org/) is the fundamental package needed for scientific computing with Python.

[Pillow](https://python-pillow.org/) is a friendly PIL(Python Imaging Library) fork.

[IPython](https://ipython.org/) is a command shell for interactive computing in multiple programming languages, originally developed for the Python programming language, that offers enhanced introspection, rich media, additional shell syntax, tab completion, and rich history.

[GraphLab Create](https://turi.com/) is a Python library, backed by a C++ engine, for quickly building large-scale, high-performance machine learning models.

[Pandas](https://pandas.pydata.org/) is a fast, powerful, and easy to use open source data structrures, data analysis and manipulation tool, built on top of the Python programming language.

[PuLP](https://coin-or.github.io/pulp/) is an Linear Programming modeler written in python. PuLP can generate LP files and call on use highly optimized solvers, GLPK, COIN CLP/CBC, CPLEX, and GUROBI, to solve these linear problems.

[Matplotlib](https://matplotlib.org/) is a 2D plotting library for creating static, animated, and interactive visualizations in Python. Matplotlib produces publication-quality figures in a variety of hardcopy formats and interactive environments across platforms.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a simple and efficient tool for data mining and data analysis. It is built on NumPy,SciPy, and mathplotlib.

# R Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279027-f1925e00-bbdd-11eb-8fd2-dc16d84086a9.png">
  <br />
</p>

## R Learning Resources

[R](https://www.r-project.org/) is an open source software environment for statistical computing and graphics. It compiles and runs on a wide variety of  platforms such as Windows and MacOS.

[An Introduction to R](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf)

[Google's R Style Guide](https://google.github.io/styleguide/Rguide.html)

[R developer's guide to Azure](https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/r-developers-guide)

[Running R at Scale on Google Compute Engine](https://cloud.google.com/solutions/running-r-at-scale)

[Running R on AWS](https://aws.amazon.com/blogs/big-data/running-r-on-aws/)

[RStudio Server Pro for AWS](https://aws.amazon.com/marketplace/pp/RStudio-RStudio-Server-Pro-for-AWS/B06W2G9PRY)

[Learn R by Codecademy](https://www.codecademy.com/learn/learn-r)

[Learn R Programming with Online Courses and Lessons by edX](https://www.edx.org/learn/r-programming)

[R Language Courses by Coursera](https://www.coursera.org/courses?query=r%20language)

[Learn R For Data Science by Udacity](https://www.udacity.com/course/programming-for-data-science-nanodegree-with-R--nd118)

## R Tools, Libraries and Frameworks

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[VSCode-R](https://marketplace.visualstudio.com/items?itemName=Ikuyadeu.r) is a VS Code extension provides support for the [R programming language](https://www.r-project.org/), including features such as extended syntax highlighting, R language service based on code analysis, interacting with R terminals, viewing data, plots, workspace variables, help pages, managing packages, and working with [R Markdown](https://rmarkdown.rstudio.com/) documents.

[R Debugger](https://marketplace.visualstudio.com/items?itemName=RDebugger.r-debugger) is an extension that adds debugging capabilities for the R programming language to Visual Studio Code and depends on the R package [vscDebugger (documentation)](https://github.com/ManuelHentschel/vscDebugger).

[Language Server Protocol (LSP)](https://microsoft.github.io/language-server-protocol/) is a tool that defines the protocol used between an editor or IDE and a language server that provides language features like auto complete, go to definition, find all references.

[Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) is the AI code completion tool trusted by millions of developers to code faster with fewer errors. Whether you are a new dev or a seasoned pro, working solo or part of a team, Tabnine will help push your productivity to new heights while cutting your QA time.

[RStudio](https://rstudio.com/) is an integrated development environment for R and Python, with a console, syntax-highlighting editor that supports direct code execution, and tools for plotting, history, debugging and workspace management.

[Shiny](https://shiny.rstudio.com/) is a newer package from RStudio that makes it incredibly easy to build interactive web applications with R.

[R Host](https://github.com/microsoft/R-Host) is a host process for R that provides access and extensibility to it remotely over WebSocket and JSON.

[Rmarkdown](https://rmarkdown.rstudio.com/) is a package helps you create dynamic analysis documents that combine code, rendered output (such as figures), and prose.

[Rplugin](https://github.com/JetBrains/Rplugin) is R Language supported plugin for the IntelliJ IDE.

[Plotly](https://plotly-r.com/) is an R package for creating interactive web graphics via the open source JavaScript graphing library [plotly.js](https://github.com/plotly/plotly.js).

[Metaflow](https://metaflow.org/) is a Python/R library that helps scientists and engineers build and manage real-life data science projects. Metaflow was originally developed at Netflix to boost productivity of data scientists who work on a wide variety of projects from classical statistics to state-of-the-art deep learning.

[Prophet](https://facebook.github.io/prophet) is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data.

[LightGBM](https://lightgbm.readthedocs.io/) is a gradient boosting framework that uses tree based learning algorithms, used for ranking, classification and many other machine learning tasks.

[Dash](https://plotly.com/dash) is a Python framework for building analytical web applications in Python, R, Julia, and Jupyter.

[MLR](https://mlr.mlr-org.com/) is Machine Learning in R.

[ML workspace](https://github.com/ml-tooling/ml-workspace) is an all-in-one web-based IDE specialized for machine learning and data science. It is simple to deploy and gets you started within minutes to productively built ML solutions on your own machines. ML workspace is the ultimate tool for developers preloaded with a variety of popular data science libraries (Tensorflow, PyTorch, Keras, and MXnet) and dev tools (Jupyter, VS Code, and Tensorboard) perfectly configured, optimized, and integrated.

[CatBoost](https://catboost.ai/) is a fast, scalable, high performance Gradient Boosting on Decision Trees library, used for ranking, classification, regression and other machine learning tasks for Python, R, Java, C++. Supports computation on CPU and GPU.

[Plumber](https://www.rplumber.io/) is a tool that allows you to create a web API by merely decorating your existing R source code with special comments.

[Drake](https://docs.ropensci.org/drake) is an R-focused pipeline toolkit for reproducibility and high-performance computing.

[DiagrammeR](https://visualizers.co/diagrammer/) is a package you can create, modify, analyze, and visualize network graph diagrams. The output can be incorporated into R Markdown documents, integrated with Shiny web apps, converted to other graph formats, or exported as image files.

[Knitr](https://yihui.org/knitr/) is a general-purpose literate programming engine in R, with lightweight API's designed to give users full control of the output without heavy coding work.

[Broom](https://broom.tidymodels.org/) is a tool that converts statistical analysis objects from R into tidy format.


# Rust Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279024-f0613100-bbdd-11eb-9b52-30c276f8cc0f.png">
  <br />
</p>

## Rust Learning Resources

[Rust](https://www.rust-lang.org) is a multi-paradigm programming language focused on performance and safety. Rust has a comparable amount of runtime to C and C++, and has set up its standard library to be amenable towards OS development. Specifically, the standard library is split into two parts: core and std. Core is the lowest-level aspects only, and doesn't include things like allocation, threading, and other higher-level features.

[The Rust Language Reference](https://doc.rust-lang.org/nightly/reference/)

[The Rust Programming Language Book](https://doc.rust-lang.org/book/)

[Learning Rust](https://www.rust-lang.org/learn)

[Why AWS loves Rust](https://aws.amazon.com/blogs/opensource/why-aws-loves-rust-and-how-wed-like-to-help/)

[Rust Programming courses on Udemy](https://www.udemy.com/courses/search/?src=ukw&q=Rust)

[Safety in Systems Programming with Rust at Standford by Ryan Eberhardt](https://reberhardt.com/blog/2020/10/05/designing-a-new-class-at-stanford-safety-in-systems-programming.html)

[WebAssembly meets Kubernetes with Krustlet using Rust](https://cloudblogs.microsoft.com/opensource/2020/04/07/announcing-krustlet-kubernetes-rust-kubelet-webassembly-wasm/)

[Microsoft's Project Verona](https://github.com/microsoft/verona/blob/master/docs/explore.md)

## Rust Tools

[Cargo](https://github.com/rust-lang/cargo) is a package manager that downloads your Rust project’s dependencies and compiles your project.

[Crater](https://crater.rust-lang.org/) is a tool to run experiments across parts of the Rust ecosystem. Its primary purpose is to detect regressions in the Rust compiler, and it does this by building a large number of crates, running their test suites and comparing the results between two versions of the Rust compiler. It can operate locally (with Docker as the only dependency) or distributed on the cloud. It can operate locally (with Docker as the only dependency) or distributed on the cloud.

[VSCode-Rust](https://github.com/rust-lang/vscode-rust) is plugin that adds language support for Rust to Visual Studio Code. Rust support is powered by a separate language server - either by the official Rust Language Server (RLS) or rust-analyzer, depending on the user's preference. If you don't have it installed, the extension will install it for you (with permission). This extension is built and maintained by the Rust IDEs and editors team with the focus on providing a stable, high quality extension that makes the best use of the respective language server.

[Apache Arrow](https://github.com/apache/arrow) is a development platform for in-memory analytics. It contains a set of technologies that enable big data systems to process and move data fast. Arrow's libraries are available for C, C++, C#, Go, Java, JavaScript, MATLAB, Python, R, Ruby, and Rust.

[Wasmer](https://wasmer.io/) enables super lightweight containers based on [WebAssembly](https://webassembly.org/) that can run anywhere such as the Desktop to the Cloud and IoT devices, and also embedded in [any programming language](https://github.com/wasmerio/wasmer#language-integrations).

[Firecracker](https://firecracker-microvm.github.io) is an open source virtualization technology that is purpose-built for creating and managing secure, multi-tenant container and function-based services that provide serverless operational models. Firecracker runs workloads in lightweight virtual machines, called microVMs, which combine the security and isolation properties provided by hardware virtualization technology with the speed and flexibility of containers. Firecracker has also been integrated in container runtimes, for example [Kata Containers](https://github.com/kata-containers/documentation/wiki/Initial-release-of-Kata-Containers-with-Firecracker-support) and [Weaveworks Ignite](https://github.com/weaveworks/ignite).

[Tokio](https://github.com/tokio-rs/tokio) is an event-driven, non-blocking I/O platform for writing asynchronous applications with the Rust programming language.

[TiKV](https://github.com/tikv/tikv) is an open-source distributed transactional key-value database that also provides classical key-vlue APIs, but also transactional APIs with ACID compliance.

[Sonic](https://crates.io/crates/sonic-server) is a fast, lightweight and schema-less search backend similar to Elasticsearch in some use-cases.

[Hyper](https://github.com/hyperium/hyper) is a fast and correct HTTP library for Rust.

[Rocket](https://github.com/SergioBenitez/Rocket) is an async web framework for Rust with a focus on usability, security, extensibility, and speed.

[Clippy](https://rust-lang.github.io/rust-clippy/) is a collection of lints to catch common mistakes and improve your Rust code.

[Servo](https://github.com/servo/servo) is a prototype web browser engine written in the Rust language.

[Vector](https://vector.dev/) is a high-performance, end-to-end (agent & aggregator) observability data platform that puts the user in control of their observability data.

[RustPython](https://github.com/RustPython/RustPython) is a Python Interpreter written in Rust.

[Miri](https://github.com/rust-lang/miri) is an interpreter for Rust's mid-level intermediate representation. It can run binaries and test suites of cargo projects and detect certain classes of undefined behavior. Miri will alsowill also tell you about memory leaks: when there is memory still allocated at the end of the execution, and that memory is not reachable from a global static, Miri will raise an error.

[Chalk](https://rust-lang.github.io/chalk/book/) is an implementation and definition of the Rust trait system using a PROLOG-like logic solver.

[stdarch](https://doc.rust-lang.org/stable/core/arch/) is Rust's standard library vendor-specific APIs and run-time feature detection.

[Simpleinfra](https://github.com/rust-lang/simpleinfra) is rep that contains the tools and automation written by the Rust infrastructure team to manage our services. Using some of the tools in this repo require privileges only infra team members have.

[Rustlings](https://github.com/rust-lang/rustlings) is a small set of exercises to get you used to reading and writing Rust code.

[Krustlet](https://krustlet.dev/) acts as a Kubernetes Kubelet(written in Rust) by listening on the event stream for new pods that the scheduler assigns to it based on specific Kubernetes [tolerations](https://kubernetes.io/docs/concepts/configuration/taint-and-toleration/). The project is currently experimental.

## Operating System

[Redox](https://www.redox-os.org) is a Unix-like Operating System written in Rust, aiming to bring the innovations of Rust to a modern microkernel and full set of applications. Acitvely being developed by [Jeremy Soeller](https://gitlab.redox-os.org/jackpot51).

[Bottlerocket OS](https://github.com/bottlerocket-os/bottlerocket) is an open-source Linux-based operating system meant for hosting containers. Bottlerocket focuses on security and maintainability, providing a reliable, consistent, and safe platform for container-based workloads.

[Tock](https://www.tockos.org) is an embedded operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M and RISC-V based embedded platforms. Tock's design centers around protection, both from potentially malicious applications and from device drivers. Tock uses two mechanisms to protect different components of the operating system. First, the kernel and device drivers are written in Rust, a systems programming language that provides compile-time memory safety, type safety and strict aliasing. Tock uses Rust to protect the kernel (the scheduler and hardware abstraction layer) from platform specific device drivers as well as isolate device drivers from each other. Second, Tock uses memory protection units to isolate applications from each other and the kernel.

[Rust on Chrome OS](https://chromium.googlesource.com/chromiumos/docs/+/master/rust_on_cros.md) is a document that provides information on creating Rust projects for installation within Chrome OS and Chrome OS SDK.

[Writing an OS in Rust ](https://os.phil-opp.com) is a blog series creates a small operating system in the Rust programming language by [Philipp Oppermann](https://github.com/phil-opp).

# Go Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719679-068f8c80-fb39-11ea-8baa-9e779ee58a0a.png">
  <br />
</p>

## Go Learning Resources

[Go](https://golang.org/) is an open source programming language that makes it easy to build simple, reliable, and efficient software.

[Golang Contribution Guide](https://golang.org/doc/contribute.html)

[Google Developers Training](https://developers.google.com/training/)

[Google Developers Certification](https://developers.google.com/certification/)

[Uber's Go Style Guide](https://github.com/uber-go/guide/blob/master/style.md)

[GitLab's Go standards and style guidelines](https://docs.gitlab.com/ee/development/go_guide/)

[Effective Go](https://golang.org/doc/effective_go.html)

[Go: The Complete Developer's Guide (Golang) on Udemy](https://www.udemy.com/course/go-the-complete-developers-guide/)

[Getting Started with Go on Coursera](https://www.coursera.org/learn/golang-getting-started)

[Programming with Google Go on Coursera](https://www.coursera.org/specializations/google-golang)

[Learning Go Fundamentals on Pluralsight](https://www.pluralsight.com/courses/go-fundamentals)

[Learning Go on Codecademy](https://www.codecademy.com/learn/learn-go)

## Go Tools and Frameworks

[golang tools](https://pkg.go.dev/golang.org/x/tools) holds the source for various packages and tools that support the Go programming language.

[Go in Visual Studio Code](https://code.visualstudio.com/docs/languages/go) is an extension that gives you language features like IntelliSense, code navigation, symbol search, bracket matching, snippets, and many more that will help you in Golang development.

[Traefik](https://github.com/traefik/traefik) is a modern HTTP reverse proxy and load balancer that makes deploying microservices easy. Traefik integrates with your existing infrastructure components (Docker, Swarm mode, Kubernetes, Marathon, Consul, Etcd, Rancher, Amazon ECS, etc.) and configures itself automatically and dynamically. Pointing Traefik at your orchestrator should be the only configuration step you need.

[Gitea](https://github.com/go-gitea/gitea) is Git with a cup of tea, painless self-hosted git service. Using Go, this can be done with an independent binary distribution across all platforms which Go supports, including Linux, macOS, and Windows on x86, amd64, ARM and PowerPC architectures.

[OpenFaaS](https://github.com/openfaas/faas) is Serverless Functions Made Simple. It makes it easy for developers to deploy event-driven functions and microservices to Kubernetes without repetitive, boiler-plate coding. Package your code or an existing binary in a Docker image to get a highly scalable endpoint with auto-scaling and metrics.

[micro](https://github.com/zyedidia/micro) is a terminal-based text editor that aims to be easy to use and intuitive, while also taking advantage of the capabilities of modern terminals. As its name indicates, micro aims to be somewhat of a successor to the nano editor by being easy to install and use. It strives to be enjoyable as a full-time editor for people who prefer to work in a terminal, or those who regularly edit files over SSH.

[Gravitational Teleport](https://github.com/gravitational/teleport) is a modern security gateway for remotely accessing into Clusters of Linux servers via SSH or SSH-over-HTTPS in a browser or Kubernetes clusters.

[NATS](https://nats.io/) is a simple, secure and performant communications system for digital systems, services and devices. NATS is part of the Cloud Native Computing Foundation (CNCF). NATS has over 30 client language implementations, and its server can run on-premise, in the cloud, at the edge, and even on a Raspberry Pi. NATS can secure and simplify design and operation of modern distributed systems.

[Act](https://github.com/nektos/act) is a GO program that allows you to run our GitHub Actions locally.

[Fiber](https://gofiber.io/) is an [Express](https://github.com/expressjs/express) inspired web framework built on top of [Fasthttp](https://github.com/valyala/fasthttp), the fastest HTTP engine for Go. Designed to ease things up for fast development with zero memory allocation and performance in mind.

[Glide](https://github.com/Masterminds/glide) is a vendor Package Management for Golang.

[BadgerDB](https://github.com/dgraph-io/badger) is an embeddable, persistent and fast key-value (KV) database written in pure Go. It is the underlying database for [Dgraph](https://dgraph.io/), a fast, distributed graph database. It's meant to be a performant alternative to non-Go-based key-value stores like RocksDB.

[Go kit](https://github.com/go-kit/kit) is a programming toolkit for building microservices (or elegant monoliths) in Go. We solve common problems in distributed systems and application architecture so you can focus on delivering business value.

[Codis](https://github.com/CodisLabs/codis) is a proxy based high performance Redis cluster solution written in Go.

[zap](https://github.com/uber-go/zap) is a blazing fast, structured, leveled logging in Go.

[HttpRouter](https://github.com/julienschmidt/httprouter) is a lightweight high performance HTTP request router (also called multiplexer or just mux for short) for Go.

[Gorilla WebSocket](https://github.com/gorilla/websocket) is a Go implementation of the WebSocket protocol.

[Delve](https://github.com/go-delve/delve) is a debugger for the Go programming language.

[GORM](https://github.com/go-gorm/gorm) is a fantastic ORM library for Golang, aims to be developer friendly.

[Go Patterns](https://github.com/tmrts/go-patterns) is a curated collection of idiomatic design & application patterns for Go language.


# Swift Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719675-03949c00-fb39-11ea-8f81-bf4cd544c17f.png">
  <br />
</p>

## Swift Learning Resources

[Swift](https://developer.apple.com/swift/) is Apple's main programming language for iOS, macOS, watchOS, and tvOS app development. Though, many parts of Swift will be familiar to developers from their experience of developing in C and Objective-C.

[Swift Evolution](https://github.com/apple/swift-evolution) maintains proposals for changes and user-visible enhancements to the Swift Programming Language.

[Xcode + Swift](https://developer.apple.com/swift/resources/) makes developing applications for MacOS and iOS fast and fun.

[Swift 5.3 Basics](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)

[Start Developing iOS Apps with Swift](https://developer.apple.com/library/archive/referencelibrary/GettingStarted/DevelopiOSAppsSwift/)

[Apple Developer Documentation](https://developer.apple.com/documentation)

[Apple Foundation Framework](https://developer.apple.com/documentation/foundation)

[Apple Core Animation Framework](https://developer.apple.com/documentation/quartzcore)

[Apple Core Graphics Framework](https://developer.apple.com/documentation/coregraphics)

[Getting Started with LLDB](https://developer.apple.com/library/archive/documentation/IDEs/Conceptual/gdb_to_lldb_transition_guide/document/lldb-basics.html)

[Mac Catalyst - iOS - Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/ios/overview/mac-catalyst/)

[Amazon EC2 Mac Instances](https://aws.amazon.com/ec2/instance-types/mac/)

[Swift GitHub](https://github.com/apple/swift)

[Apple Developer Forums](https://developer.apple.com/forums/)

[Swift Forums](https://forums.swift.org/)

[Google's Swift Style Guide](https://google.github.io/swift/)

[Swift Courses Online from Coursera](https://www.coursera.org/courses?query=swift)

[Swift Courses Online from Udemy](https://www.udemy.com/topic/swift/)

[Learning Swift course from Codecademy](https://www.codecademy.com/learn/learn-swift)

## Swift Tools and Frameworks

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 12 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Mac Catalyst](https://developer.apple.com/mac-catalyst/) is a set of Apple APIs that developers can use to rapidly port their iOS apps to [Apple Silicon M1 Chip](https://www.apple.com/mac/m1/) and take full advantage of the new capabilities on the new Apple hardware.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[Cocoapods](https://cocoapods.org/) is a dependency manager for Swift and Objective-C used in Xcode projects by specifying the dependencies for your project in a simple text file. CocoaPods then recursively resolves dependencies between libraries, fetches source code for all dependencies, and creates and maintains an Xcode workspace to build your project.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages.

[Vapor](https://github.com/vapor/vapor) is a web framework for Swift. It provides a beautifully expressive and easy to use foundation for your next website, API, or cloud project.

[Hero](https://github.com/HeroTransitions/Hero) is a library for building iOS view controller transitions. It provides a declarative layer on top of the UIKit's cumbersome transition APIs—making custom transitions an easy task for developers.

[Kingfisher](https://github.com/onevcat/Kingfisher) is a powerful, pure-Swift library for downloading and caching images from the web. It provides you a chance to use a pure-Swift way to work with remote images in your next app.

[Realm](https://github.com/realm/realm-cocoa) is a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the iOS, macOS, tvOS & watchOS versions of Realm Swift & Realm Objective-C.

[Perfect](https://github.com/PerfectlySoft/Perfect) is a complete and powerful toolbox, framework, and application server for Linux, iOS, and macOS (OS X). It provides everything a Swift engineer needs for developing lightweight, maintainable, and scalable apps and other REST services entirely in the Swift programming language for both client-facing and server-side applications.

[Alamofire](https://github.com/Alamofire/Alamofire) is an HTTP networking library written in Swift.

[Eureka](https://github.com/xmartlabs/Eureka) is an elegant iOS form builder in Swift

[Carthage](https://github.com/Carthage/Carthage) is intended to be the simplest way to add frameworks to your Cocoa application. Carthage builds your dependencies and provides you with binary frameworks, but you retain full control over your project structure and setup. Carthage does not automatically modify your project files or your build settings.

[ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) is reactive extensions to Cocoa frameworks, built on top of ReactiveSwift.

# Ruby Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719684-07282300-fb39-11ea-98fd-90394a2df6f2.png">
  <br />
</p>

## Ruby Learning Resources

[Ruby](https://www.ruby-lang.org/en/) is a dynamic, open source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write.

[Ruby Documentation](https://www.ruby-lang.org/en/documentation/)

[Ruby Community](https://www.ruby-lang.org/en/community/)

[Ruby Gems](https://guides.rubygems.org/rubygems-basics/)

[Ruby courses by Coursera](https://www.coursera.org/courses?query=ruby)

[Learn Ruby course by Codecademy](https://www.codecademy.com/learn/learn-ruby)

[Ruby Glossary](https://www.codecademy.com/articles/glossary-ruby)

[Ruby in Twenty Minutes Quickstart](https://www.ruby-lang.org/en/documentation/quickstart/)

[Getting started with a Ruby on Rails application on CircleCI.](https://circleci.com/docs/2.0/language-ruby/)

[The Ruby Style Guide](https://rubystyle.guide)

[Airbnb's Ruby Style Guide](https://github.com/airbnb/ruby)

## Ruby Tools and Frameworks

[RubyMine](https://www.jetbrains.com/ruby/) is a professional IDE developed by Jet Brains that provides support for Ruby, Ruby on Rails and web development.

[Rails](https://rubyonrails.org/) is a web-application framework that includes everything needed to create database-backed web applications according to the [Model-View-Controller (MVC)](https://en.wikipedia.org/wiki/Model-view-controller) pattern. Understanding the MVC pattern is key to understanding Rails. MVC divides your application into three layers: Model, View, and Controller, each with a specific responsibility.

[rbenv](https://github.com/rbenv/rbenv) allows to pick a Ruby version for your application and guarantee that your development environment matches production. Put rbenv to work with Bundler for painless Ruby upgrades and bulletproof deployments.

[Prettier for Ruby](https://prettier.io/) is a plugin for the Ruby programming language and its ecosystem. prettier is an opinionated code formatter that supports multiple languages and integrates with most editors. The idea is to eliminate discussions of style in code review and allow developers to get back to thinking about code design instead.

[Active Admin](https://activeadmin.info/) is a Ruby on Rails framework for creating elegant backends for website administration.

[Capistrano](https://github.com/capistrano/capistrano) is a framework for building automated deployment scripts. Although Capistrano itself is written in Ruby, it can easily be used to deploy projects of any language or framework, be it Rails, Java, or PHP.

[Spree](https://spreecommerce.org/) is an open source E-commerce platform for Rails 6 with a modern UX, optional PWA frontend, REST API, GraphQL, several official extensions and 3rd party integrations.

[Sidekiq](https://sidekiq.org/) is a simple, efficient background processing for Ruby. It uses hreads to handle many jobs at the same time in the same process. It does not require Rails but will integrate tightly with Rails to make background processing dead simple.

[Kaminari](https://github.com/amatsuda/kaminari/wiki) is a  Scope and Engine based, clean, powerful, and customizable  paginator for modern web app frameworks and ORMs.

[React-Rails](https://github.com/reactjs/react-rails) is a flexible tool to use [React](http://facebook.github.io/react/) with Rails. By integrating React.js with Rails views and controllers, the asset pipeline, or webpacker.

[Pry](https://github.com/pry/pry) is a runtime developer console and IRB alternative with powerful introspection capabilities.

[Brakeman](https://brakemanscanner.org/) is a static analysis tool which checks Ruby on Rails applications for security vulnerabilities.

[dotenv](https://github.com/bkeepers/dotenv) is a Ruby gem to load environment variables from `.env`.

[Scientist](https://github.com/github/scientist) is a Ruby library for carefully refactoring critical paths.

[fastlane](https://fastlane.tools/) is a tool written in Ruby for iOS and Android developers to automate tedious tasks like generating screenshots, dealing with provisioning profiles, and releasing your application.

[Fluentd](https://www.fluentd.org/) collects events from various data sources and writes them to files, RDBMS, NoSQL, IaaS, SaaS, Hadoop and so on all written in Ruby.

# PHP Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93925949-bf85d080-fccb-11ea-9158-d8d967a03e60.png">
  <br />

</p>

**[Start building with PHP on Azure](https://aka.ms/azsdk/php)**

**[PHP Documentation](https://docs.microsoft.com/en-us/azure/app-service/quickstart-php)**

## PHP Learning Resources

[PHP](https://www.php.net/) is a popular general-purpose scripting language that is especially suited to web development. Fast, flexible and pragmatic, PHP powers everything from your blog to the most popular websites in the world.

[PHP 8](https://www.php.net/releases/8.0/en.php)

[What's New in PHP 8 - Auth0](https://auth0.com/blog/whats-new-php-8/)

[PHP Manual](https://www.php.net/manual/en/index.php)

[MIT's PHP Code Style Guide](https://mitsloan.mit.edu/shared/content/PHP_Code_Style_Guide.php)

[PHP Style Guide](https://gist.github.com/ryansechrest/8138375)

[PHP tutorial by W3Schools](https://www.w3schools.com/php/)

[PHP MySQL & CodeIgniter Course on Udemy](https://www.udemy.com/course/php-mysql-codeigniter-complete-guide/)

## Tools

[PhpStorm](https://www.jetbrains.com/phpstorm/) is a professional PHP IDE developed by Jet Brains for working with Symfony, Laravel, Drupal, WordPress, Laminas, Magento, Joomla!, CakePHP, Yii, and other frameworks.

[Laravel](https://laravel.com/) is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling.

[PHP Tools for Visual Studio/VS Code](https://www.devsense.com/en) is a an extension that turn Visual Studio into a powerful PHP development environment.

[Symfony](https://symfony.com/) is a PHP framework for web and console applications and a set of reusable PHP components. Symfony is used by thousands of web applications (including BlaBlaCar.com and Spotify.com) and most of the [popular PHP projects](https://symfony.com/projects) (including Drupal and Magento).

[CakePHP](https://cakephp.org) is a rapid development framework for PHP which uses commonly known design patterns like Associative Data Mapping, Front Controller, and MVC. CakePHP's main goal is to provide a structured framework that enables PHP users at all levels to rapidly develop robust web applications, without any loss to flexibility.

[Composer](https://getcomposer.org/) is a tools helps you declare, manage, and install dependencies of PHP projects.

[Guzzle](https://github.com/guzzle/guzzle) is a PHP HTTP client that makes it easy to send HTTP requests and trivial to integrate with web services.

[DesignPatternsPHP](https://designpatternsphp.readthedocs.io/) is a collection of known design patterns and some sample code how to implement them in PHP 7.4. Every pattern has a small list of examples.

[CodeIgniter](https://codeigniter.com/) is an Application Development Framework for people who build web sites using PHP. Its goal is to enable you to develop projects much faster than you could if you were writing code from scratch, by providing a rich set of libraries for commonly needed tasks, as well as a simple interface and logical structure to access these libraries. CodeIgniter lets you creatively focus on your project by minimizing the amount of code needed for a given task.

[HHVM](https://hhvm.com/) is an open-source virtual machine designed for executing programs written in [Hack](https://hacklang.org/). HHVM uses a just-in-time (JIT) compilation approach to achieve superior performance while maintaining amazing development flexibility. HHVM should be used together with a webserver like the built in, easy to deploy [Proxygen](https://docs.hhvm.com/hhvm/basic-usage/proxygen), or a [FastCGI-based](https://docs.hhvm.com/hhvm/advanced-usage/fastCGI) webserver on top of nginx or Apache.

[PHPUnit](https://phpunit.de/) is a programmer-oriented testing framework for PHP. It is an instance of the xUnit architecture for unit testing frameworks.

[Phalcon](https://phalcon.io/) is an open source web framework delivered as a C extension for the PHP language providing high performance and lower resource consumption.

[Swoole](https://www.swoole.co.uk/) is an event-driven asynchronous & coroutine-based concurrency networking communication engine with high performance written in C and C++ for PHP.

[Matomo](https://matomo.org/) is a full-featured PHP MySQL software program that you download and install on your own webserver. At the end of the five-minute installation process, you will be given a JavaScript code. Simply copy and paste this tag on websites you wish to track and access your analytics reports in real-time.

[Grav](https://getgrav.org/) is a Fast, Simple, and Flexible, file-based Web-platform. There is Zero installation required. Just extract the ZIP archive, and you are already up and running. It follows similar principles to other flat-file CMS platforms, but has a different design philosophy than most. Grav comes with a powerful Package Management System to allow for simple installation and upgrading of plugins and themes, as well as simple updating of Grav itself.

[Whoops](https://filp.github.io/whoops/) is an error handler framework for PHP. Out-of-the-box, it provides a pretty error interface that helps you debug your web projects, but at heart it's a simple yet powerful stacked error handling system.

[Slim](https://www.slimframework.com/) is a PHP micro framework that helps you quickly write simple yet powerful web applications and APIs.

# Flutter Development
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719686-0abbaa00-fb39-11ea-978d-91e55844dd7a.png">
</p>

[Flutter](https://flutter.dev/) is Google's UI toolkit for crafting beautiful, natively compiled applications for mobile(Andorid and iOS), web, and desktop(Windows, MacOS, Linux, and Google Fuchsia) from a single codebase. Flutter works with existing code, is used by developers and organizations around the world, and is free and open source.

## Flutter Learning Resources

[Flutter Gems](https://fluttergems.dev) is a curated package guide for Flutter which functionally categorizes some of the most useful and popular flutter packages available on pub.dev Flutter Gems A Flutter package landscape guide comprising 1500+ neatly categorized useful and popular packages.

[Dart](https://dart.dev/) is an open-source, scalable programming language, with robust libraries and runtimes, for building web, server, and mobile apps using the Flutter framework.

[Flutter documentation](https://flutter.dev/docs)

[Style Guide for Flutter](https://github.com/flutter/flutter/wiki/Style-guide-for-Flutter-repo)

[Creating your first Flutter app](https://flutter.dev/docs/get-started/codelab)

[Build and release an Android app using Flutter](https://flutter.dev/docs/deployment/android)

[Flutter Tools & techniques](https://flutter.dev/docs/development/tools)

[Dart and Flutter: The Complete Developer's Guide on Udemy](https://www.udemy.com/course/dart-and-flutter-the-complete-developers-guide/)

[Creating an Interactive Story with Flutter on Coursera](https://www.coursera.org/projects/story-creating-flutter)

[Flutter for Beginners course on Pluralsight](https://www.pluralsight.com/courses/flutter-getting-started)

[Flutter Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/flutter)

[The Complete Flutter App Development Bootcamp with Dart by App Brewery](https://www.appbrewery.co/p/flutter-development-bootcamp-with-dart)

[Adding Firebase to your Flutter app](https://firebase.google.com/docs/flutter/setup)

[Using Firebase and Firestore with Flutter](https://flutter.dev/docs/development/data-and-backend/firebase)

[Fuchsia Project](https://fuchsia.dev/)

[Getting Started with Fuchsia](https://fuchsia.dev/fuchsia-src/get-started)

[Fuchsia Reference](https://fuchsia.dev/reference)

[Contributing to Fuchsia](https://fuchsia.dev/fuchsia-src/CONTRIBUTING)

## Flutter Tools

[Firebase](https://firebase.google.com/) is a Backend-as-a-Service (BaaS) app development platform that provides hosted backend services such as a realtime database, cloud storage, authentication, crash reporting, machine learning, remote configuration, and hosting for your static files.

[FlutterFire](https://firebase.flutter.dev/) is a set of [Flutter plugins](https://flutter.io/platform-plugins/) that enable Flutter apps to use [Firebase](https://firebase.google.com/) services. You can follow an example that shows how to use these plugins in the [Firebase for Flutter](https://codelabs.developers.google.com/codelabs/flutter-firebase/index.html#0) codelab.

[FlutterBoost](https://github.com/alibaba/flutter_boost) is a Flutter plugin which enables hybrid integration of Flutter for your existing native apps with minimum efforts.

[Go-flutter](https://github.com/go-flutter-desktop/go-flutter) is a package that brings Flutter to the desktop. project implements the [Flutter's Embedding API](https://github.com/flutter/flutter/wiki/Custom-Flutter-Engine-Embedders) using a single code base that runs on Windows, macOS, and Linux. For rendering, [GLFW](https://github.com/go-gl/glfw) fits the job because it provides the right abstractions over the OpenGL's Buffer/Mouse/Keyboard for each platform.

[Appwrite](https://appwrite.io/) is a secure end-to-end backend server for Web, Mobile, and Flutter developers that is packaged as a set of Docker containers for easy deployment.

[Fluro](https://github.com/theyakka/fluro) is a Flutter routing library that adds flexible routing options like wildcards, named parameters and clear route definitions.

# Networking
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/82833053-d1687b80-9e71-11ea-8c6d-074100f2f54b.png">
  <br />
</p>

## Network Learning Resources

[AWS Certified Security - Specialty Certification](https://aws.amazon.com/certification/certified-security-specialty/)

[Microsoft Certified: Azure Security Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-security-engineer)

[Google Cloud Certified Professional Cloud Security Engineer](https://cloud.google.com/certification/cloud-security-engineer)

[Cisco Security Certifications](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/security.html)

[The Red Hat Certified Specialist in Security: Linux](https://www.redhat.com/en/services/training/ex415-red-hat-certified-specialist-security-linux-exam)

[Linux Professional Institute LPIC-3 Enterprise Security Certification](https://www.lpi.org/our-certifications/lpic-3-303-overview)

[Cybersecurity Training and Courses from IBM Skills](https://www.ibm.com/skills/topics/cybersecurity/)

[Cybersecurity Courses and Certifications by Offensive Security](https://www.offensive-security.com/courses-and-certifications/)

[Citrix Certified Associate – Networking(CCA-N)](http://training.citrix.com/cms/index.php/certification/networking/)

[Citrix Certified Professional – Virtualization(CCP-V)](https://www.globalknowledge.com/us-en/training/certification-prep/brands/citrix/section/virtualization/citrix-certified-professional-virtualization-ccp-v/)

[CCNP Routing and Switching](https://learningnetwork.cisco.com/s/ccnp-enterprise)

[Certified Information Security Manager(CISM)](https://www.isaca.org/credentialing/cism)

[Wireshark Certified Network Analyst (WCNA)](https://www.wiresharktraining.com/certification.html)

[Juniper Networks Certification Program Enterprise (JNCP)](https://www.juniper.net/us/en/training/certification/)

[Networking courses and specializations from Coursera](https://www.coursera.org/browse/information-technology/networking)

[Network & Security Courses from Udemy](https://www.udemy.com/courses/it-and-software/network-and-security/)

[Network & Security Courses from edX](https://www.edx.org/learn/cybersecurity)

## Networking Tools & Concepts

[cURL](https://curl.se/) is a computer software project providing a library and command-line tool for transferring data using various network protocols(HTTP, HTTPS, FTP, FTPS, SCP, SFTP, TFTP, DICT, TELNET, LDAP LDAPS, MQTT, POP3, POP3S, RTMP, RTMPS, RTSP, SCP, SFTP, SMB, SMBS, SMTP or SMTPS). cURL is also used in cars, television sets, routers, printers, audio equipment, mobile phones, tablets, settop boxes, media players and is the Internet transfer engine for thousands of software applications in over ten billion installations.

[cURL Fuzzer](https://github.com/curl/curl-fuzzer) is a quality assurance testing for the curl project.

[DoH](https://github.com/curl/doh) is a stand-alone application for DoH (DNS-over-HTTPS) name resolves and lookups.

[Authelia](https://www.authelia.com/) is an open-source highly-available authentication server providing single sign-on capability and two-factor authentication to applications running behind [NGINX](https://nginx.org/en/).

[nginx(engine x)](https://nginx.org/en/) is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server, originally written by Igor Sysoev.

[Proxmox Virtual Environment(VE)](https://www.proxmox.com/en/) is a complete open-source platform for enterprise virtualization. It inlcudes a built-in web interface that you can easily manage VMs and containers, software-defined storage and networking, high-availability clustering, and multiple out-of-the-box tools on a single solution.

[Wireshark](https://www.wireshark.org/) is a very popular network protocol analyzer that is commonly used for network troubleshooting, analysis, and communications protocol development. Learn more about the other useful [Wireshark Tools](https://wiki.wireshark.org/Tools) available.

[HTTPie](https://github.com/httpie/httpie) is a command-line HTTP client. Its goal is to make CLI interaction with web services as human-friendly as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers.

[HTTPStat](https://github.com/reorx/httpstat) is a tool that visualizes curl statistics in a simple layout.

[Wuzz](https://github.com/asciimoo/wuzz) is an interactive cli tool for HTTP inspection. It can be used to inspect/modify requests copied from the browser's network inspector with the "copy as cURL" feature.

[Websocat](https://github.com/vi/websocat) is a ommand-line client for WebSockets, like netcat (or curl) for ws:// with advanced socat-like functions.

    • Connection: In networking, a connection refers to pieces of related information that are transferred through a network. This generally infers that a connection is built before the data transfer (by following the procedures laid out in a protocol) and then is deconstructed at the at the end of the data transfer.

    • Packet: A packet is, generally speaking, the most basic unit that is transferred over a network. When communicating over a network, packets are the envelopes that carry your data (in pieces) from one end point to the other.

Packets have a header portion that contains information about the packet including the source and destination, timestamps, network hops. The main portion of a packet contains the actual data being transferred. It is sometimes called the body or the payload.

    • Network Interface: A network interface can refer to any kind of software interface to networking hardware. For instance, if you have two network cards in your computer, you can control and configure each network interface associated with them individually.

A network interface may be associated with a physical device, or it may be a representation of a virtual interface. The "loop-back" device, which is a virtual interface to the local machine, is an example of this.

    • LAN: LAN stands for "local area network". It refers to a network or a portion of a network that is not publicly accessible to the greater internet. A home or office network is an example of a LAN.

    • WAN: WAN stands for "wide area network". It means a network that is much more extensive than a LAN. While WAN is the relevant term to use to describe large, dispersed networks in general, it is usually meant to mean the internet, as a whole.
If an interface is connected to the WAN, it is generally assumed that it is reachable through the internet.

    • Protocol: A protocol is a set of rules and standards that basically define a language that devices can use to communicate. There are a great number of protocols in use extensively in networking, and they are often implemented in different layers.

Some low level protocols are TCP, UDP, IP, and ICMP. Some familiar examples of application layer protocols, built on these lower protocols, are HTTP (for accessing web content), SSH, TLS/SSL, and FTP.

    • Port: A port is an address on a single machine that can be tied to a specific piece of software. It is not a physical interface or location, but it allows your server to be able to communicate using more than one application.

    • Firewall: A firewall is a program that decides whether traffic coming into a server or going out should be allowed. A firewall usually works by creating rules for which type of traffic is acceptable on which ports. Generally, firewalls block ports that are not used by a specific application on a server.

    • NAT: Network address translation is a way to translate requests that are incoming into a routing server to the relevant devices or servers that it knows about in the LAN. This is usually implemented in physical LANs as a way to route requests through one IP address to the necessary backend servers.

    • VPN: Virtual private network is a means of connecting separate LANs through the internet, while maintaining privacy. This is used as a means of connecting remote systems as if they were on a local network, often for security reasons.

## Network Layers

	While networking is often discussed in terms of topology in a horizontal way, between hosts, its implementation is layered in a vertical fashion throughout a computer or network. This means is that there are multiple technologies and protocols that are built on top of each other in order for communication to function more easily. Each successive, higher layer abstracts the raw data a little bit more, and makes it simpler to use for applications and users. It also allows you to leverage lower layers in new ways without having to invest the time and energy to develop the protocols and applications that handle those types of traffic.

	As data is sent out of one machine, it begins at the top of the stack and filters downwards. At the lowest level, actual transmission to another machine takes place. At this point, the data travels back up through the layers of the other computer. Each layer has the ability to add its own "wrapper" around the data that it receives from the adjacent layer, which will help the layers that come after decide what to do with the data when it is passed off.

	One method of talking about the different layers of network communication is the OSI model. OSI stands for Open Systems Interconnect.This model defines seven separate layers. The layers in this model are:

    • Application: The application layer is the layer that the users and user-applications most often interact with. Network communication is discussed in terms of availability of resources, partners to communicate with, and data synchronization.

    • Presentation: The presentation layer is responsible for mapping resources and creating context. It is used to translate lower level networking data into data that applications expect to see.

    • Session: The session layer is a connection handler. It creates, maintains, and destroys connections between nodes in a persistent way.

    • Transport: The transport layer is responsible for handing the layers above it a reliable connection. In this context, reliable refers to the ability to verify that a piece of data was received intact at the other end of the connection. This layer can resend information that has been dropped or corrupted and can acknowledge the receipt of data to remote computers.

    • Network: The network layer is used to route data between different nodes on the network. It uses addresses to be able to tell which computer to send information to. This layer can also break apart larger messages into smaller chunks to be reassembled on the opposite end.

    • Data Link: This layer is implemented as a method of establishing and maintaining reliable links between different nodes or devices on a network using existing physical connections.

    • Physical: The physical layer is responsible for handling the actual physical devices that are used to make a connection. This layer involves the bare software that manages physical connections as well as the hardware itself (like Ethernet).

The TCP/IP model, more commonly known as the Internet protocol suite, is another layering model that is simpler and has been widely adopted.It defines the four separate layers, some of which overlap with the OSI model:

    • Application: In this model, the application layer is responsible for creating and transmitting user data between applications. The applications can be on remote systems, and should appear to operate as if locally to the end user.
The communication takes place between peers network.

    • Transport: The transport layer is responsible for communication between processes. This level of networking utilizes ports to address different services. It can build up unreliable or reliable connections depending on the type of protocol used.

    • Internet: The internet layer is used to transport data from node to node in a network. This layer is aware of the endpoints of the connections, but does not worry about the actual connection needed to get from one place to another. IP addresses are defined in this layer as a way of reaching remote systems in an addressable manner.

    • Link: The link layer implements the actual topology of the local network that allows the internet layer to present an addressable interface. It establishes connections between neighboring nodes to send data.

### Interfaces
**Interfaces** are networking communication points for your computer. Each interface is associated with a physical or virtual networking device. Typically, your server will have one configurable network interface for each Ethernet or wireless internet card you have. In addition, it will define a virtual network interface called the "loopback" or localhost interface. This is used as an interface to connect applications and processes on a single computer to other applications and processes. You can see this referenced as the "lo" interface in many tools.

## Network Protocols

Networking works by piggybacks on a number of different protocols on top of each other. In this way, one piece of data can be transmitted using multiple protocols encapsulated within one another.

**Media Access Control(MAC)** is a communications protocol that is used to distinguish specific devices. Each device is supposed to get a unique MAC address during the manufacturing process that differentiates it from every other device on the internet. Addressing hardware by the MAC address allows you to reference a device by a unique value even when the software on top may change the name for that specific device during operation. Media access control is one of the only protocols from the link layer that you are likely to interact with on a regular basis.

**The IP protocol** is one of the fundamental protocols that allow the internet to work. IP addresses are unique on each network and they allow machines to address each other across a network. It is implemented on the internet layer in the IP/TCP model. Networks can be linked together, but traffic must be routed when crossing network boundaries. This protocol assumes an unreliable network and multiple paths to the same destination that it can dynamically change between. There are a number of different implementations of the protocol. The most common implementation today is IPv4, although IPv6 is growing in popularity as an alternative due to the scarcity of IPv4 addresses available and improvements in the protocols capabilities.

**ICMP: internet control message protocol** is used to send messages between devices to indicate the availability or error conditions. These packets are used in a variety of network diagnostic tools, such as ping and traceroute. Usually ICMP packets are transmitted when a packet of a different kind meets some kind of a problem. Basically, they are used as a feedback mechanism for network communications.

**TCP: Transmission control protocol** is implemented in the transport layer of the IP/TCP model and is used to establish reliable connections. TCP is one of the protocols that encapsulates data into packets. It then transfers these to the remote end of the connection using the methods available on the lower layers. On the other end, it can check for errors, request certain pieces to be resent, and reassemble the information into one logical piece to send to the application layer. The protocol builds up a connection prior to data transfer using a system called a three-way handshake. This is a way for the two ends of the communication to acknowledge the request and agree upon a method of ensuring data reliability. After the data has been sent, the connection is torn down using a similar four-way handshake. TCP is the protocol of choice for many of the most popular uses for the internet, including WWW, FTP, SSH, and email. It is safe to say that the internet we know today would not be here without TCP.

**UDP: User datagram protocol** is a popular companion protocol to TCP and is also implemented in the transport layer. The fundamental difference between UDP and TCP is that UDP offers unreliable data transfer. It does not verify that data has been received on the other end of the connection. This might sound like a bad thing, and for many purposes, it is. However, it is also extremely important for some functions. It’s not required to wait for confirmation that the data was received and forced to resend data, UDP is much faster than TCP. It does not establish a connection with the remote host, it simply fires off the data to that host and doesn't care if it is accepted or not. Since UDP is a simple transaction, it is useful for simple communications like querying for network resources. It also doesn't maintain a state, which makes it great for transmitting data from one machine to many real-time clients. This makes it ideal for VOIP, games, and other applications that cannot afford delays.

**HTTP: Hypertext transfer protocol** is a protocol defined in the application layer that forms the basis for communication on the web. HTTP defines a number of functions that tell the remote system what you are requesting. For instance, GET, POST, and DELETE all interact with the requested data in a different way.

**FTP: File transfer protocol** is in the application layer and provides a way of transferring complete files from one host to another. It is inherently insecure, so it is not recommended for any externally facing network unless it is implemented as a public, download-only resource.

**DNS: Domain name system** is an application layer protocol used to provide a human-friendly naming mechanism for internet resources. It is what ties a domain name to an IP address and allows you to access sites by name in your browser.

**SSH: Secure shell** is an encrypted protocol implemented in the application layer that can be used to communicate with a remote server in a secure way. Many additional technologies are built around this protocol because of its end-to-end encryption and ubiquity. There are many other protocols that we haven't covered that are equally important. However, this should give you a good overview of some of the fundamental technologies that make the internet and networking possible.

[REST(REpresentational State Transfer)](https://www.codecademy.com/articles/what-is-rest) is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other.

[JSON Web Token (JWT)](https://jwt.io) is a compact URL-safe means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signature (JWS).

[OAuth 2.0](https://oauth.net/2/) is an open source authorization framework that enables applications to obtain limited access to user accounts on an HTTP service, such as Amazon, Google, Facebook, Microsoft, Twitter GitHub, and DigitalOcean. It works by delegating user authentication to the service that hosts the user account, and authorizing third-party applications to access the user account.

# Databases
[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279004-daec0700-bbdd-11eb-9662-b1fc86ec8448.png">
  <br />
</p>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279002-da537080-bbdd-11eb-9d7a-44efb52f3506.png">
  <br />
</p>

## SQL/NoSQL Learning Resources

[SQL](https://en.wikipedia.org/wiki/SQL) is a standard language for storing, manipulating and retrieving data in relational databases.

[NoSQL](https://www.ibm.com/cloud/blog/sql-vs-nosql) is a database that is interchangeably referred to as "nonrelational, or "non-SQL" to highlight that the database can handle huge volumes of rapidly changing, unstructured data in different ways than a relational (SQL-based) database with rows and tables.

[Transact-SQL(T-SQL)](https://docs.microsoft.com/en-us/sql/t-sql/language-reference) is a Microsoft extension of SQL with all of the tools and applications communicating to a SQL database by sending T-SQL commands.

[Introduction to Transact-SQL](https://docs.microsoft.com/en-us/learn/modules/introduction-to-transact-sql/)

[SQL Tutorial by W3Schools](https://www.w3schools.com/sql/)

[Learn SQL Skills Online from Coursera](https://www.coursera.org/courses?query=sql)

[SQL Courses Online from Udemy](https://www.udemy.com/topic/sql/)

[SQL Online Training Courses from LinkedIn Learning](https://www.linkedin.com/learning/topics/sql)

[Learn SQL For Free from Codecademy](https://www.codecademy.com/learn/learn-sql)

[GitLab's SQL Style Guide](https://about.gitlab.com/handbook/business-ops/data-team/platform/sql-style-guide/)

[OracleDB SQL Style Guide Basics](https://oracle.readthedocs.io/en/latest/sql/basics/style-guide.html)

[Tableau CRM: BI Software and Tools](https://www.salesforce.com/products/crm-analytics/overview/)

[Databases on AWS](https://aws.amazon.com/products/databases/)

[Best Practices and Recommendations for SQL Server Clustering in AWS EC2.](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/aws-sql-clustering.html)

[Connecting from Google Kubernetes Engine to a Cloud SQL instance.](https://cloud.google.com/sql/docs/mysql/connect-kubernetes-engine)

[Educational Microsoft Azure SQL resources](https://docs.microsoft.com/en-us/sql/sql-server/educational-sql-resources?view=sql-server-ver15)

[MySQL Certifications](https://www.mysql.com/certification/)

[SQL vs. NoSQL Databases: What's the Difference?](https://www.ibm.com/cloud/blog/sql-vs-nosql)

[What is NoSQL?](https://aws.amazon.com/nosql/)

## SQL/NoSQL Tools and Databases

[Netdata](https://github.com/netdata/netdata) is high-fidelity infrastructure monitoring and troubleshooting, real-time monitoring Agent collects thousands of metrics from systems, hardware, containers, and applications with zero configuration. It runs permanently on all your physical/virtual servers, containers, cloud deployments, and edge/IoT devices, and is perfectly safe to install on your systems mid-incident without any preparation.

[Azure Data Studio](https://github.com/Microsoft/azuredatastudio) is an open source data management tool that enables working with SQL Server, Azure SQL DB and SQL DW from Windows, macOS and Linux.

[Azure SQL Database](https://azure.microsoft.com/en-us/services/sql-database/)  is the intelligent, scalable, relational database service built for the cloud. It’s evergreen and always up to date, with AI-powered and automated features that optimize performance and durability for you. Serverless compute and Hyperscale storage options automatically scale resources on demand, so you can focus on building new applications without worrying about storage size or resource management.

[Azure SQL Managed Instance](https://azure.microsoft.com/en-us/services/azure-sql/sql-managed-instance/) is a fully managed SQL Server Database engine instance that's hosted in Azure and placed in your network. This deployment model makes it easy to lift and shift your on-premises applications to the cloud with very few application and database changes. Managed instance has split compute and storage components.

[Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) is a limitless analytics service that brings together enterprise data warehousing and Big Data analytics. It gives you the freedom to query data on your terms, using either serverless or provisioned resources at scale. It brings together the best of the SQL technologies used in enterprise data warehousing, Spark technologies used in big data analytics, and Pipelines for data integration and ETL/ELT.

[MSSQL for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql) is an extension for developing Microsoft SQL Server, Azure SQL Database and SQL Data Warehouse everywhere with a rich set of functionalities.

[SQL Server Data Tools (SSDT)](https://docs.microsoft.com/en-us/sql/ssdt/download-sql-server-data-tools-ssdt) is a development tool for building SQL Server relational databases, Azure SQL Databases, Analysis Services (AS) data models, Integration Services (IS) packages, and Reporting Services (RS) reports. With SSDT, a developer can design and deploy any SQL Server content type with the same ease as they would develop an application in Visual Studio or Visual Studio Code.

[Bulk Copy Program](https://docs.microsoft.com/en-us/sql/tools/bcp-utility) is a command-line tool that comes with Microsoft SQL Server. BCP, allows you to import and export large amounts of data in and out of SQL Server databases quickly snd efficeiently.

[SQL Server Migration Assistant](https://www.microsoft.com/en-us/download/details.aspx?id=54258) is a tool from Microsoft that simplifies database migration process from Oracle to SQL Server, Azure SQL Database, Azure SQL Database Managed Instance and Azure SQL Data Warehouse.

[SQL Server Integration Services](https://docs.microsoft.com/en-us/sql/integration-services/sql-server-integration-services?view=sql-server-ver15) is a development platform for building enterprise-level data integration and data transformations solutions. Use Integration Services to solve complex business problems by copying or downloading files, loading data warehouses, cleansing and mining data, and managing SQL Server objects and data.

[SQL Server Business Intelligence(BI)](https://www.microsoft.com/en-us/sql-server/sql-business-intelligence) is a collection of tools in Microsoft's SQL Server for transforming raw data into information businesses can use to make decisions.

[Tableau](https://www.tableau.com/) is a Data Visualization software used in relational databases, cloud databases, and spreadsheets. Tableau was acquired by [Salesforce in August 2019](https://investor.salesforce.com/press-releases/press-release-details/2019/Salesforce-Completes-Acquisition-of-Tableau/default.aspx).

[DataGrip](https://www.jetbrains.com/datagrip/) is a professional DataBase IDE developed by Jet Brains that provides context-sensitive code completion, helping you to write SQL code faster. Completion is aware of the tables structure, foreign keys, and even database objects created in code you're editing.

[RStudio](https://rstudio.com/) is an integrated development environment for R and Python, with a console, syntax-highlighting editor that supports direct code execution, and tools for plotting, history, debugging and workspace management.

[MySQL](https://www.mysql.com/) is a fully managed database service to deploy cloud-native applications using the world's most popular open source database.

[PostgreSQL](https://www.postgresql.org/) is a powerful, open source object-relational database system with over 30 years of active development that has earned it a strong reputation for reliability, feature robustness, and performance.

[Amazon DynamoDB](https://aws.amazon.com/dynamodb/) is a key-value and document database that delivers single-digit millisecond performance at any scale. It is a fully managed, multiregion, multimaster, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications.

[Apache Cassandra™](https://cassandra.apache.org/) is an open source NoSQL distributed database trusted by thousands of companies for scalability and high availability without compromising performance. Cassandra provides linear scalability and proven fault-tolerance on commodity hardware or cloud infrastructure make it the perfect platform for mission-critical data.

[Apache HBase™](https://hbase.apache.org/) is an open-source, NoSQL, distributed big data store. It enables random, strictly consistent, real-time access to petabytes of data. HBase is very effective for handling large, sparse datasets. HBase serves as a direct input and output to the Apache MapReduce framework for Hadoop, and works with Apache Phoenix to enable SQL-like queries over HBase tables.

[Hadoop Distributed File System (HDFS)](https://www.ibm.com/analytics/hadoop/hdfs) is a distributed file system that handles large data sets running on commodity hardware. It is used to scale a single Apache Hadoop cluster to hundreds (and even thousands) of nodes. HDFS is one of the major components of Apache Hadoop, the others being [MapReduce](https://www.ibm.com/analytics/hadoop/mapreduce) and [YARN](https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html).

[Apache Mesos](http://mesos.apache.org/) is a cluster manager that provides efficient resource isolation and sharing across distributed applications, or frameworks. It can run Hadoop, Jenkins, Spark, Aurora, and other frameworks on a dynamically shared pool of nodes.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for big data processing, with built-in modules for streaming, SQL, machine learning and graph processing.

[ElasticSearch](https://www.elastic.co/) is a search engine based on the Lucene library. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents. Elasticsearch is developed in Java.

[Logstash](https://www.elastic.co/products/logstash) is a tool for managing events and logs. When used generically, the term encompasses a larger system of log collection, processing, storage and searching activities.

[Kibana](https://www.elastic.co/products/kibana) is an open source data visualization plugin for Elasticsearch. It provides visualization capabilities on top of the content indexed on an Elasticsearch cluster. Users can create bar, line and scatter plots, or pie charts and maps on top of large volumes of data.

[Trino](https://trino.io/) is a Distributed SQL query engine for big data. It is able to tremendously speed up [ETL processes](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl), allow them all to use standard SQL statement, and work with numerous data sources and targets all in the same system.

[Extract, transform, and load (ETL)](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl) is a data pipeline used to collect data from various sources, transform the data according to business rules, and load it into a destination data store.

[Redis(REmote DIctionary Server)](https://redis.io/) is an open source (BSD licensed), in-memory data structure store, used as a database, cache, and message broker. It provides data structures such as strings, hashes, lists, sets, sorted sets with range queries, bitmaps, hyperloglogs, geospatial indexes, and streams.

[FoundationDB](https://www.foundationdb.org/) is an open source distributed database designed to handle large volumes of structured data across clusters of commodity servers. It organizes data as an ordered key-value store and employs ACID transactions for all operations. It is especially well-suited for read/write workloads but also has excellent performance for write-intensive workloads. FoundationDB was acquired by [Apple in 2015](https://techcrunch.com/2015/03/24/apple-acquires-durable-database-company-foundationdb/).

[IBM DB2](https://www.ibm.com/analytics/db2) is a collection of hybrid data management products offering a complete suite of AI-empowered capabilities designed to help you manage both structured and unstructured data on premises as well as in private and public cloud environments. Db2 is built on an intelligent common SQL engine designed for scalability and flexibility.

[MongoDB](https://www.mongodb.com/) is a document database meaning it stores data in JSON-like documents.

[OracleDB](https://www.oracle.com/database/) is a powerful fully managed database helps developers manage business-critical data with the highest availability, reliability, and security.

[MariaDB](https://mariadb.com/) is an enterprise open source database solution for modern, mission-critical applications.

[SQLite](https://sqlite.org/index.html) is a C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.SQLite is the most used database engine in the world. SQLite is built into all mobile phones and most computers and comes bundled inside countless other applications that people use every day.

[SQLite Database Browser](https://sqlitebrowser.org/) is an open source SQL tool that allows users to create, design and edits SQLite database files. It lets users show a log of all the SQL commands that have been issued by them and by the application itself.

[InfluxDB](https://www.influxdata.com/) is an open source time series platform.  This includes APIs for storing and querying data, processing it in the background for [ETL](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl) or monitoring and alerting purposes, user dashboards, Internet of Things sensor data, and visualizing and exploring the data and more. It also has support for processing data from [Graphite](http://graphiteapp.org/).

[Atlas](https://github.com/Netflix/atlas) is an in-memory dimensional [time series database](https://en.wikipedia.org/wiki/Time_series_database).

[CouchbaseDB](https://www.couchbase.com/) is an open source distributed [multi-model NoSQL document-oriented database](https://en.wikipedia.org/wiki/Multi-model_database). It creates a key-value store with managed cache for sub-millisecond data operations, with purpose-built indexers for efficient queries and a powerful query engine for executing SQL queries.

[dbWatch](https://www.dbwatch.com/) is a complete database monitoring/management solution for SQL Server, Oracle, PostgreSQL, Sybase, MySQL and Azure. Designed for proactive management and automation of routine maintenance in large scale on-premise, hybrid/cloud database environments.

[Cosmos DB Profiler](https://hibernatingrhinos.com/products/cosmosdbprof) is a real-time visual debugger allowing a development team to gain valuable insight and perspective into their usage of Cosmos DB database. It identifies over a dozen suspicious behaviors from your application’s interaction with Cosmos DB.

[Adminer](https://www.adminer.org/) is an SQL management client tool for managing databases, tables, relations, indexes, users. Adminer has support for all the popular database management systems such as MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Firebird, SimpleDB, Elasticsearch and MongoDB.

[DBeaver](https://dbeaver.io/) is an open source database tool for developers and database administrators. It offers supports for JDBC compliant databases such as MySQL, Oracle, IBM DB2, SQL Server, Firebird, SQLite, Sybase, Teradata, Firebird, Apache Hive, Phoenix, and Presto.

[DbVisualizer](https://dbvis.com/) is a SQL management tool that allows users to manage a wide range of databases such as Oracle, Sybase, SQL Server, MySQL, H3, and SQLite.

[AppDynamics Database](https://www.appdynamics.com/supported-technologies/database) is a management product for Microsoft SQL Server. With AppDynamics you can monitor and trend key performance metrics such as resource consumption, database objects, schema statistics and more, allowing you to proactively tune and fix issues in a High-Volume Production Environment.

[Toad](https://www.quest.com/toad/) is a SQL Server DBMS toolset developed by Quest. It increases productivity by using extensive automation, intuitive workflows, and built-in expertise. This SQL management tool resolve issues, manage change and promote the highest levels of code quality for both relational and non-relational databases.

[Lepide SQL Server](https://www.lepide.com/sql-storage-manager/) is an open source storage manager utility to analyse the performance of SQL Servers. It provides a complete overview of all configuration and permission changes being made to your SQL Server environment through an easy-to-use, graphical user interface.

[Sequel Pro](https://sequelpro.com/) is a fast MacOS database management tool for working with MySQL. This SQL management tool helpful for interacting with your database by easily to adding new databases, new tables, and new rows.


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/VSCode-Guide/pulls).


## License

[Back to the Top](https://github.com/mikeroyal/VSCode-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/)

