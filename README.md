# You Shall Not DEPLOY 🛑✨

![image](https://github.com/user-attachments/assets/b6d75c22-ad28-4ade-a120-d290421076de)

## Description
**You Shall Not DEPLOY** is a solution designed to help development teams avoid deployments on risky days, such as Fridays, weekends, and public holidays. By using this tool, you can ensure greater production stability by preventing changes during times prone to issues.

## Features
- 🚫 Blocks deployments on Fridays.
- 🚫 Prevents deployments during weekends.
- 🚫 Respects a customizable list of public holidays.
- ✅ Easy integration with CI/CD pipelines using GitHub Actions.
- ✅ Flexible setup to add custom deployment commands and steps.

## How It Works
The workflow checks the current date before initiating the deployment process. If the date falls on a blocked day (Friday, weekend, or a specified holiday), the pipeline is automatically halted, preventing any changes from being pushed to production.

## How to Implement
1. **Create the Workflow**: Add a specific workflow to your repository that checks the date before allowing deployments.
2. **Python Script**: The repository includes a script that verifies the date against the blocked days.
3. **Customize Your Deployment**: Adjust the deployment steps according to your project's requirements.

## Benefits
- 🔒 **Security**: Reduces the risk of production issues by blocking deployments on critical days.
- ⚙️ **Automation**: Simple integration with GitHub Actions to automate deployment checks.
- 📅 **Flexibility**: Easily customize the list of holidays and blocked days as needed.

## Contributions
Contributions are welcome! If you have ideas for new features or improvements, feel free to open an *issue* or submit a *pull request*.
