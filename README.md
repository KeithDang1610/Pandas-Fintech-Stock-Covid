## Utilize Python and libraries (Pandas, Numpy,..) to calculate and investigate the impact of the COVID-19 pandemic on the relationship between abnormal returns and investor behavioral biases in 100 randomly selected Japanese stock companies. 

### Objectives and deliveries:
- Collect data from the original resources (such as: Eikon platform, financial APIs...), in this case, using data from Eikon
- Calculate and manipulate the relevant factors and variables that encompass various aspects of human behavior in financial strategies:
  - Abnormal Returns (dependent variable):
    - $$AR_{i,t} = R_{i,t} - E(R_{i,t})$$;
  - Herding Behaviors (indendepent variable):
    - $$HI_t = \frac{1}{N} \sum_{i=1}^{N} \left( \frac{|r_{i,t} - r_{m,t}|}{|r_{m,t}|} \right)$$;
  - Loss Aversion (indendepent variable):
    - $$X_{i,t+1} = S_{i,t} R_{i,t+1} - S_{i,t} R_{f,t} \quad $$;
  - Overconfidence (indendepent variable):
    - $$TR = \frac{V_{i,t}}{N_{i,t}}$$;
  - Mental Accounting (indendepent variable):
    - $$K = \frac{P_0}{D_0} \quad $$;
    - $$SMR = \text{Portfolio A} - \text{Portfolio B} \quad$$;
- 4 tables, including:
  - Descriptive statistics
  - Johansen cointegration Test
  - Granger causality Test
  - Linear Regression (OLS)
 
### Tools and Libraries:
- Python
- Pandas
- Numpy
- Statsmodel
- Matplotlib
- Seaborn
