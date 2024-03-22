## Welcome to Fix by Some Engineering Inc. 👋

<p align="center">
  <img src="https://cdn.some.engineering/assets/fix-logos/fix-logo.svg" alt="FIX Logo" width="200" height="200">
</p>


### Who We Are 🌟
At [Some Engineering Inc.](https://some.engineering), our expertise lies in pioneering cloud security and infrastructure management solutions. We are dedicated to transforming the complexity of cloud environments into streamlined, user-friendly systems. Our goal is to empower businesses of various scales to manage and secure their cloud infrastructure with ease and efficiency.


### Our Projects 🚀
- **[Fix](https://fix.security)**: Our latest SaaS offering in the Cloud Security Posture Management (CSPM) space. Build on Fix Inventory, Fix is designed to help organizations secure their cloud infrastructure efficiently. It comprises of these components:
  - [`fixfrontend`](https://github.com/someengineering/fixfrontend): The Fix user interface for managing and monitoring your cloud security posture.
  - [`fixbackend`](https://github.com/someengineering/fixbackend): The backend that powers the Fix platform.
  - [`fixctl`](https://github.com/someengineering/fixctl): The Fix CLI tool for integrating Fix data into your pipelines.
  - [`fix-cf`](https://github.com/someengineering/fix-cf): The sources for the AWS CloudFormation stack that Fix deploys.
  - [`fixcloudutils`](https://github.com/someengineering/fixcloudutils): Various utilities used in Fix.
- **[Fix Inventory](https://inventory.fix.security)**: Our established self-hosted cloud inventory tool, powering our SaaS offerings with reliability and flexibility. 🛠️ Fix Inventory is the backbone, facilitating resource management and optimization. It comprises of these components:
  - [`fixinventory`](https://github.com/someengineering/fixinventory):
    - [`fixcore`](https://github.com/someengineering/fixinventory/tree/main/fixcore): The Fix graph platform core. Receives infrastructure data from the worker(s), runs workflows and infrastructure apps and provides and API.
    - [`fixworker`](https://github.com/someengineering/fixinventory/tree/main/fixworker): Runs [collector plugins](https://github.com/someengineering/fixinventory/tree/main/plugins) and sends the result to fixcore.
    - [`fixshell`](https://github.com/someengineering/fixinventory/tree/main/fixshell): CLI to interact with Fix Inventory.
    - [`fixmetrics`](https://github.com/someengineering/fixinventory/tree/main/fixmetrics): Fix Inventory Prometheus metrics exporter.
  - [`fixcompliance`](https://github.com/someengineering/fixcompliance): Our compliance benchmarks and checks. Used by `fixcore` to find vulnerable cloud resources.
  - [`fixinventoryclient`](https://github.com/someengineering/fixinventoryclient-python): Python SDK for accessing Fix Inventory. Used by `fixshell`.
  - [`fixinventory-apps`](https://github.com/someengineering/fixinventory-apps): A collection of Fix Inventory infrastructure apps. Used by `fixcore` to dynamically react to changes in your infrastructure.
  - [`fixinventoryappbundler`](https://github.com/someengineering/fixinventoryappbundler): A bundler that takes a collection of infrastructure app sources and bundles them into a single json for `fixcore` to consume. Also allows to dry-run apps during development.
  - [`fixdatalink`](https://github.com/someengineering/fixdatalink): Data Pipelines for Fix Inventory infrastructure data. Used by `fixcore` to export inventory data to PostgreSQL, MySQL/MariaDB, Snowflake, etc.


### Open Source Commitment 💖
We believe in the power of open source. All our products are open source, inviting collaboration, innovation, and transparency. Fix Inventory is fully self contained and can be deployed on your laptop or in the cloud. We've invested heavily in its documentation, ensuring it is accessible and user-friendly for everyone. In contrast, FIX frontend and backend are distinctly designed projects. They are open source primarily for auditability and transparency. We actively develop these in the public domain, but they are specifically tailored to support our FIX SaaS system, and we frequently introduce breaking changes. It's also important to note that while FIX frontend is open source, it utilizes commercial Material UI components. As such, to use it, you'd need your own Material UI license.


### Join the Conversation 🗣️
Have questions or want to discuss cloud management and security? Join us on [our Discord](https://discord.gg/someengineering) and be part of our growing community.

---
Stay updated and connect with us on [LinkedIn](https://linkedin.com/company/fix) 📱
