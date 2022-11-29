{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "f4e01c50",
   "metadata": {},
   "source": [
    "## Advanced Regression"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "62ee6720",
   "metadata": {},
   "source": [
    "### Problem Statement"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "6f06d77d",
   "metadata": {},
   "source": [
    "A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.\n",
    "The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.\n",
    "\n",
    "The company wants to know:\n",
    "- Which variables are significant in predicting the price of a house, and\n",
    "- How well those variables describe the price of a house.\n",
    "\n",
    "Also, determine the optimal value of lambda for ridge and lasso regression."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "f7b56c5c",
   "metadata": {},
   "source": [
    "### Business Goal"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "1c0512d3",
   "metadata": {},
   "source": [
    "You are required to model the price of houses with the available independent variables. \n",
    "This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "0c31b51a",
   "metadata": {},
   "source": [
    "### Observation"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "be1fba93",
   "metadata": {},
   "source": [
    "- Best alpha value for Lasso : {'alpha': 0.001} \n",
    "- Best alpha value for Ridge : {'alpha': 0.1}"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "72676ee1",
   "metadata": {},
   "source": [
    "After comparing both the models we figure that below features are best explaining the data set\n",
    "- LotConfig_FR2\n",
    "- KitchenAbvGr\n",
    "- Condition2_Norm\n",
    "- ExterQual\n",
    "- 2ndFlrSF\n",
    "- Fireplaces\n",
    "- LotConfig_Inside\n",
    "- BedroomAbvGr\n",
    "- BsmtFinSF2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "962b0b37",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.12"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
