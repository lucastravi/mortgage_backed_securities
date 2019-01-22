# DATA SCIENCE EXERCISE - MORTGAGE BACK SECURITIES

Credit risk is a problem we face on a daily basis on our Data Science team. You have received in an email a mortgage
backed securities database on 50k mortgages. The database contains features about the mortgage contract, payment of
each installment and the economic environment. Understanding and cleaning up the data is your responsibility. We are
interested in how you handle the problems you will encounter.

## DATA DICTIONARY

  - id: Borrower ID
  - time: Time stamp of observation
  - orig_time: Time stamp for origination
  - first_time: Time stamp for first observation
  - mat_time: Time stamp for maturity
  - balance_time: Outstanding balance at observation time
  - LTV_time: Loan-to-value ratio at observation time, in %
  - interest_rate_time: Interest rate at observation time, in %
  - hpi_time: House price index at observation time, base year = 100
  - gdp_time: Gross domestic product (GDP) growth at observation time, in %
  - uer_time: Unemployment rate at observation time, in %
  - REtype_CO_orig_time: Real estate type condominium = 1, otherwise = 0
  - REtype_PU_orig_time: Real estate type planned urban development = 1, otherwise = 0
  - REtype_SF_orig_time: Single-family home = 1, otherwise = 0
  - investor_orig_time: Investor borrower = 1, otherwise = 0
  - balance_orig_time: Outstanding balance at origination time
  - FICO_orig_time: FICO score at origination time, in %
  - LTV_orig_time: Loan-to-value ratio at origination time, in %
  - Interest_Rate_orig_time: Interest rate at origination time, in %
  - hpi_orig_time: House price index at origination time, base year = 100
  - default_time: Default observation at observation time
  - payoff_time: Payoff observation at observation time
  - status_time: Default (1), payoff (2), and nondefault/nonpayoff (0) observation at observation time
