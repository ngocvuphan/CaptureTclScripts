# OrCAD Capture TCL Scripts

## Load the scripts

- Run OrCAD Capture
- Open "Command Window"
  ![Command Window](https://user-images.githubusercontent.com/756333/227448023-ad642229-d8e6-41d8-9033-2ba0a8346445.png)

- Append the scripts path into the TCL packages search path

```
lappend ::auto_path {PATH OF SCRIPTS DIRECTORY}
```

- Run the app manager

```
package require AppManager
```

- Open a DSN schematic. The "Utilities" menu is added into end of menu list
  ![Commands](https://user-images.githubusercontent.com/756333/227448103-721cca00-745e-40a1-a256-7b7684ea6e92.png)

## Activate the scripts

- Run "Utilities > Update License..."
- Send the "Request Code" to the scripts's author
- Fill the "Activation Code" when received
- Click on Activate button to activate the scripts
  ![Activate the scripts](https://user-images.githubusercontent.com/756333/227448109-8a68203a-64b8-402e-a88b-32ef34bc6ce3.png)

## Scripts Usage

### DisplayProperty

- Copy and paste part display properties
  ![Copy and paste part display properties](https://user-images.githubusercontent.com/756333/227448114-6729d352-ac10-4bfe-a9fb-246864eb6819.gif)

- Extract and apply the part display properties template
  ![Extract and apply the part display properties template](https://user-images.githubusercontent.com/756333/227448134-089f7efb-e36d-4466-b9b0-accebe6b66c2.gif)
