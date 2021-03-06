---
title: Generating Doxygen Documentation
nav_order: 2
parent: Documenting Python Code
---

# Generating Doxygen Documentation
{:.no_toc}

This page goes over the steps required to generate Doxygen documentation from code that was written with our [best practices](../best_practices/best_practices.md).

* TOC
{:toc}

1. Open the Doxygen GUI, "doxywizard", by opening the Windows Start Menu, typing "doxywizard" into the prompt, and hitting <kbd>Enter</kbd>.
    ![Step 1](imgs/step_1.png)
2. Hit the `Select` button for selecting the folder with which Doxygen will run.
    ![Step 2](imgs/step_2.png)
3. In the dialog box that opens, select where in your repository you would like Doxygen to put the generated documentation and click `Select Folder`.
    ![Step 3](imgs/step_3.png)
4. Enter the project name and description in the prompts.
    ![Step 4](imgs/step_4.png)
5. Click the `Select...` button for specifying the directory where the project's source code is.
    ![Step 5](imgs/step_5.png)
6. Select the source code directory for your project in the dialog box and click the `Select Folder` button.
    ![Step 6](imgs/step_6.png)
7. In the main GUI menu, select the `Scan recursively` checkbox.
    ![Step 7](imgs/step_7.png)
8. Press the `Select...` button to choose the directory where the generated documentation will go. 
    ![Step 8](imgs/step_8.png)
9. Click the `Select Folder` button on the pop-up dialog. You won't have to select a new folder if you followed step 3 correctly.
    ![Step 9](imgs/step_9.png)
10. Click the `Next` button to advance to the "Mode" menu.
    ![Step 10](imgs/step_10.png)
11. Select the "All Entities", "Include cross-referenced source code in the output", and "Optimize for Java or C# output" options and click the `Next` button to advance the the "Output" menu.
    ![Step 11](imgs/step_11.png)
12. Under the "HTML" options, select "with navigation panel". Deselct the "LaTeX" option. Click the `Next` button to advance the "Diagrams" menu.
    ![Step 12](imgs/step_12.png)
13. Click the `Next` button to advance to the "Run" menu. You don't need to do any customization here.
    ![Step 13](imgs/step_13.png)
14. Click the `Run Doxygen` button and allow Doxygen to run.
    ![Step 14](imgs/step_14.png)
15. Click the `Show HTML output` button.
    ![Step 15](imgs/step_15.png)
16. Verify that the documentation was generated correctly. And begin exploring your documented code!
    ![Step 16](imgs/step_16.png)
