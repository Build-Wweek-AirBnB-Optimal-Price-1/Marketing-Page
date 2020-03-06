# Marketing Page

This is the landing page for a web application/data science project that predicts the optimal price for an Airbnb listing. It accomplishes this by taking as an input some information about the listing and using a machine learning model trained on Berlin area listings data to find the optimal price. We've called it Optimalbnb. 

## Installing and running preprocessor LESS

I used the LESS preprocessor. If you don't already have it installed you may use the following commands to do so. (You will need to have installed Homebrew and Yarn first)

```bash
yarn global add less
```

```bash
yarn global add less-watch-compiler
```

Then to run the LESS compiler you use the following command inside of the root of the project.

```bash
less-watch-compiler less css index.less
```
