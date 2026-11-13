# UI lab results

Tool parts that I chose:

## Part 0
- Step 0.1, Chrome version: 158.0.8127.18 (Official Build) (arm64) 
- Step 0.3, ChromeDriver version: ChromeDriver 158.0.8127.18
- Step 0.4, locator of Pizza, Please!: $x("//button[normalize-space()='Pizza, Please!']")
- Step 0.4, locator of Excluded tools: $x("//label[normalize-space()='Excluded tools']/following-sibling::select")
- Step 0.4, locator of Must be vegetarian: $x("//input[@id='default-checkbox' and @type='checkbox']")
- Step 0.4, locator of Custom Pizza Name: document.querySelector("input#pizza-name")
- Step 0.5, pizza name, tool and calories of the run by hand: Crisp, Scissors, 375

| Step | Actual result | Pass or fail |
|------|---------------|--------------|
| 1    | The heading reads Looking to break out of your pizza routine? | Pass |
| 2    | Max Calories per Slice, Excluded tools, Must be vegetarian and Custom Pizza Name appear | pass |
| 3    | The fields show these values | pass |
| 4    | Our recommendation:
Name: Crisp
Dough: Thick
Ingredients:
Olive oil
Bianco di Nizza tomatoes
Mozzarella
Parmesan cheese
Garlic
Tool: Scissors
Calories per slice: 375 | pass |
| 5    | The page says Please log in first. | pass |
| 6    | The page shows Latest pizza recommendations | pass |
| 7    | The line shows the pizza name with the same tool as in step 4 | pass |

## Part 1: Selenium IDE
- Firefox version and Node.js version: Firefox version: 151.0.2 Node.js version: v22.14.0
- Step 1.4, the line of the failed check and the line Tests:
- Step 1.5, target chosen for Submit, and why the recorded one was fragile:
- Step 1.6, commands changed, added or deleted after recording:
- Step 1.6, the pizza names of run 1 and run 2, from the lines info: echo:
- Step 1.6, the line Tests: of both runs:
- Step 1.7, one line of QP01customerTest.java that needs rewriting, and why:

## Part 2: Selenium WebDriver in Java
- Step 2.4, the failure line for the wrong title:
- Step 2.15, QP01Test run 1, result and time:
- Step 2.15, QP01Test run 2, result and time:
- Step 2.20, full run 1, time and number of tests:
- Step 2.20, full run 2, time and number of tests:

## Part 3: Robot Framework
- robot --version:
- Step 3.2, failure message for the wrong title:
- Step 3.8, run 1, result, elapsed time and pizza name:
- Step 3.8, run 2, result, elapsed time and pizza name:

## Part 4: Cypress
- node --version, npm --version and npx cypress version:
- Step 4.3, failure message for the wrong title:
- Step 4.6, tool and calories in the answer of POST /api/pizza:
- Step 4.7, the line of the admin list that shows your pizza:
- Step 4.8, run 1, result, duration and pizza name:
- Step 4.8, run 2, result, duration and pizza name:
- Step 4.9 (optional), browser and result:

## Part B
1.
2.
3.
4.
5.
6.
7.