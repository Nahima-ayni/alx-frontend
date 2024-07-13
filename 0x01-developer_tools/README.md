## Developer Tools Guide

### What are Developer Tools?

Developer Tools, commonly referred to as DevTools, are a set of web authoring and debugging tools built into modern web browsers. These tools help developers inspect, debug, and analyze the performance of web applications.

### How to Open Developer Tools

**Google Chrome:**
1. Right-click on the page and select **Inspect**.
2. Or use the keyboard shortcut `Ctrl + Shift + I` (Windows/Linux) or `Cmd + Option + I` (Mac).

**Mozilla Firefox:**
1. Right-click on the page and select **Inspect Element**.
2. Or use the keyboard shortcut `Ctrl + Shift + I` (Windows/Linux) or `Cmd + Option + I` (Mac).

**Safari:**
1. Enable the Develop menu by going to **Safari > Preferences > Advanced** and checking **Show Develop menu in menu bar**.
2. Then, select **Develop > Show Web Inspector**.
3. Or use the keyboard shortcut `Cmd + Option + I`.

**Microsoft Edge:**
1. Right-click on the page and select **Inspect**.
2. Or use the keyboard shortcut `Ctrl + Shift + I` (Windows/Linux) or `Cmd + Option + I` (Mac).

### Using the Elements Tab to Edit HTML and CSS

1. Open Developer Tools and navigate to the **Elements** tab.
2. Click on any HTML element in the DOM tree to inspect it.
3. Edit HTML: Double-click an element or right-click and select **Edit as HTML** to make changes.
4. Edit CSS: In the **Styles** pane, you can add, edit, or delete CSS properties. Any changes will reflect in real-time on the webpage.

### Auditing a Page with Lighthouse

1. Open Developer Tools and navigate to the **Lighthouse** tab.
2. Click **Generate report**.
3. Lighthouse will audit the page and provide a report with scores and tips in categories such as Performance, Accessibility, Best Practices, SEO, and PWA.
4. Follow the suggestions to improve your webpage.

### Creating and Running Snippets

1. Open Developer Tools and navigate to the **Sources** tab.
2. Go to the **Snippets** sub-tab.
3. Click the **New Snippet** button and write your JavaScript code.
4. Right-click the snippet and select **Run** to execute it on the current page.

### Getting Information About Files and Server Configurations

1. Open Developer Tools and navigate to the **Network** tab.
2. Reload the page to see network requests.
3. Click on any request to see details such as headers, response, cookies, and more.

### Blocking Requests

1. Open Developer Tools and navigate to the **Network** tab.
2. Right-click on a network request and select **Block request URL**.
3. The selected request will be blocked and will not be made in future reloads.

### Knowing How Much JavaScript or CSS is Used on a Page

1. Open Developer Tools and navigate to the **Coverage** tab.
2. Click the reload button to start capturing coverage data.
3. After the page reloads, the Coverage tab will show how much JavaScript and CSS is used or unused.

### Detecting 404 Issues

1. Open Developer Tools and navigate to the **Network** tab.
2. Reload the page and look for requests with a 404 status code in the **Status** column.
3. Click on the 404 request to get more details and identify the missing resources.

### Moving Elements on a Webpage

1. Open Developer Tools and navigate to the **Elements** tab.
2. Drag and drop elements directly within the DOM tree to move them.
3. This will reflect immediately on the webpage.
