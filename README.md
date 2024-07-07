# Customer Lifetime Value (CLV) Analysis

## Introduction

Customer lifetime value (CLV), sometimes referred to as customer lifetime value, is a prediction of the net profit a company expects from its future relationship with a customer. This model can vary in complexity, from simple calculations to sophisticated predictive analytics.

CLV is a critical metric because it helps determine the maximum amount that can be spent to acquire new customers, thus playing a crucial role in evaluating the payback of marketing expenses within marketing mix modeling.

## Definition of CLTV

The present value of future cash flows attributed to the customer throughout their entire relationship with the company.

This analysis represents a single time period and provides projections for both 3-month and 6-month intervals.

## Methodology

We will estimate lifetime value with medium and long-term projections by including the specific patterns of the entire customer population, extracting the conditional probability distribution, and generalizing these patterns to the characteristics of individual customers.

### Formula

**Probabilistic lifetime value estimation with time projection:**

\[ \text{CLTV} = \left( \frac{\text{Customer Value}}{\text{Churn Rate}} \right) \times \text{Profit Margin} \]

Where:
- **Customer Value** = Purchase Frequency \(\times\) Average Order Value
- **CLTV** = Expected Number of Transactions \(\times\) Expected Average Profit

Note: "Purchase Frequency" and "Number of Transactions" mean the same thing, as do "Average Order Value" and "Average Profit". The "Expected" qualifier introduces a probabilistic distribution element.

### Caution

The expected statements add a probabilistic distribution. Expected number of purchases and expected profitability must be calculated.

- **BG/NBD** = Expected Transaction
- **Gamma Gamma** = Expected Profit

### How It Works

Statistics and probability patterns are incorporated into the formula. BG/NBD and Gamma Gamma models will be used to:
1. Model the purchasing behavior of all customers.
2. Replace an individual's characteristics in this model to predict their expected number of transactions and profitability.

### Models

- **BG/NBD Model**: A statistical model to predict the number of transactions a customer will make in a future time period.
- **Gamma Gamma Model**: A statistical model to predict the average monetary value of a customer's transactions.

## Business Problem

### An e-commerce company wants to segment its customers and tailor marketing strategies accordingly. Different campaigns are to be organized for new customers versus campaigns aimed at retaining highly profitable customers.

### The dataset includes sales between 01/12/2009 - 09/12/2011.

### In this project, the years 2010-2011 will be examined.

#### The product catalog of this company includes souvenirs.

### The vast majority of the company's customers are corporate customers.

## Variables
### Invoice: Invoice number. The unique number of each transaction, namely the invoice. Aborted operation if it starts with C.

### StockCode: Product code. Unique number for each product.

## Description: Product name

### Quantity: Number of products. It expresses how many of the products on the invoices have been sold.

### InvoiceDate: Invoice date and time.

### UnitPrice: Product price (in GBP)

### CustomerID: Unique customer number

### Country: The country where the customer lives.

