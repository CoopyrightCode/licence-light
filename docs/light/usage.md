# Usage Guide

You may use the CoopyrightCode Light License (v1.1) code for non-commercial purposes. This guide provides detailed instructions on how to apply the license to your project, create derivative works, and indicate your compliance using badges or other methods.

## 1. Using the License

To ensure proper application of the CoopyrightCode Light (v1.1) License, you need to follow these steps:

### Step 1: Add the License to Your Git Repository

1. Copy the full license text from [here](licence.md) or the repository where the license is published.
2. In the root directory of your Git repository, create a new file named `LICENSE.md` (or `LICENSE.txt` if preferred).
3. Paste the full CoopyrightCode Light License (v1.1) text into this file and save it.
4. After adding the license file, commit the changes to your Git repository by running:

    ``` { bash, .copy }
    git add LICENSE
    git commit -m "Add CoopyrightCode Light License"
    git push origin main
    ```

!!! success
    This ensures that your project is officially licensed under the CoopyrightCode Light (v1.1) and accessible to others under the same terms.

### Step 2: Include a License Notice in Your README

To make it clear that your project is under the CoopyrightCode Light License, it is recommended to add a notice in your `README.md` file.

1. Open your `README.md` file in the root directory of your repository.
2. Add a "License" section, like so:

    ``` { markdown , .copy }
    ## License

    This project is licensed under the CoopyrightCode Light License (v1.1). You may use, copy, modify, and 
    distribute the source code for non-commercial purposes only.  
    See the [LICENSE](./LICENSE) file for more details.
    ```

3. Commit the change:

    ``` { bash, .copy }
    git add README.md
    git commit -m "Add license notice to README"
    git push origin main
    ```

### Step 3: Use the CoopyrightCode Light Badge

To visually indicate that your project is licensed under CoopyrightCode Light (v1.1), you can include a license badge in your project’s `README.md` file.

1. Add the following Markdown badge to your `README.md` file, right under the title or "License" section:

    ```{ markdown, .copy }
    ![CoopyrightCode Light](https://img.shields.io/badge/license-CoopyrightCode%20Light-blue.svg)
    ```

!!! success
    This badge lets others know at a glance that the project uses the CoopyrightCode Light License, especially on platforms like GitHub where badges are commonly used for metadata.

    ![CoopyrightCode Light](https://img.shields.io/badge/license-CoopyrightCode%20Light-blue.svg)

### Step 4: License All Contributions

If you accept contributions to your project, it’s important to ensure that all contributors are aware of and agree to the terms of the CoopyrightCode Light License. You can:

1. **Add a `CONTRIBUTING.md` file**: This file outlines how contributors should interact with your project, including licensing requirements. You can include a section like this:

    ```{ markdown, .copy }
    ## License for Contributions

    By submitting contributions to this project, you agree that your contributions will be licensed under the same CoopyrightCode Light License (v1.1) that governs the project's source code.
    ```

2. **Commit the changes**:

    ``` { bash, .copy }
    git add CONTRIBUTING.md
    git commit -m "Add contributing guidelines"
    git push origin main
    ```

This ensures that all contributions are appropriately licensed under the same terms.

## 2. Creating and Distributing Derivative Works

The CoopyrightCode Light License allows you to modify and create derivative works from the source code as long as you comply with the non-commercial use restriction. Here’s how to proceed:

### 2.1 Modifying the Source Code

1. **Clone the repository**: Start by cloning the repository you want to modify:

    ``` { bash, .copy }
    git clone https://github.com/username/project.git
    ```

2. **Make modifications**: You can now modify the source code as needed. Ensure your changes are consistent with the original license terms.

3. **Add License to Derivative Work**: In the root directory of your modified project, include a copy of the CoopyrightCode Light License as outlined in Step 1 above. Make sure to credit the original author(s) in your `README.md` file, such as:

    ```{ markdown, .copy }
    ## Original Authors
    This project is based on [Original Project](https://github.com/original/project) by Original Author.
    ```

4. **License Derivative Works**: If you plan to distribute your modified project, ensure the license is included and the non-commercial terms are preserved. The derivative work must retain the CoopyrightCode Light License.

### 2.2 Sharing and Forking on GitHub

If you intend to share your modifications publicly, you can fork the repository and apply the same steps:

1. **Fork the repository**: Use GitHub's "Fork" button to create your own version of the repository.
2. **Apply changes and commit**: Modify the code, update the `README.md` and `LICENSE` files as needed.
3. **Submit pull requests**: If the original project allows contributions, you can submit a pull request with your changes. However, remember that any commercial usage must still comply with the future terms of the full CoopyrightCode License.

## 3. Common Scenarios and Best Practices

### Scenario 1: Using the Code in a Public Non-Commercial Project

If you are developing a non-commercial open-source project and wish to use code licensed under CoopyrightCode Light:

- Follow the steps above to include the license and badge in your repository.
- Ensure that all users of your project are aware of the non-commercial restrictions by adding clear notices in your documentation.
- Regularly update your license file if new versions of the CoopyrightCode Light License are published.

### Scenario 2: Handling Contributions to a Non-Commercial Project

To manage contributions to your non-commercial project, ensure that all contributors agree to the licensing terms:

- Add a `CONTRIBUTING.md` file explaining that all contributions will be licensed under CoopyrightCode Light (v1.1).
- Ensure that all pull requests or contributions are reviewed to ensure they comply with the non-commercial use guidelines.

### Scenario 3: Transitioning to Commercial Use (Future)

If you anticipate transitioning your project to a commercial setting in the future, keep in mind:

- You will need to obtain a separate commercial license once the full version of the CoopyrightCode License is available.
- Ensure that all contributors are made aware of this potential transition and that any future commercial use complies with the updated license terms.
