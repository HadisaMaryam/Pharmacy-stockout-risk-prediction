# Pharmacy Stockout Risk Prediction

Machine learning project for predicting pharmacy stockout risk and supporting smarter inventory decisions.

This repository includes a project website (`index.html`) with an interactive stockout risk explorer. The explorer uses a transparent baseline: the probability that demand over a product's supplier lead time exceeds stock on hand, assuming normally distributed daily demand. The sample watchlist uses illustrative numbers, not real pharmacy data.

## Publish the website with GitHub Pages

1. Push `index.html` and this README to the `main` branch.
2. Open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. The site will be available at https://hadisamaryam.github.io/Pharmacy-stockout-risk-prediction/

## Project status

- [x] Project website and risk explorer
- [ ] Dataset or documented synthetic data generator, plus data dictionary
- [ ] Exploratory notebook and formula baseline
- [ ] Trained classifier with time-based evaluation
- [ ] Daily ranked reorder report
