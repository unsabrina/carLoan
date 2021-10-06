import streamlit as st 
import numpy as np 
import pandas as pd

st.header("Hire Purchase Calculator")

readme = st.checkbox("readme first")

if readme:

    st.write("""
        This is a web app demo using [streamlit](https://streamlit.io/) library. It is hosted on [heroku](https://www.heroku.com/). You may get the codes via [github](https://github.com/unsabrina/myfirstapp)
        """)

    #st.write ("For more info, please contact:")

    #st.write("<a href='https://www.linkedin.com/in/ungku-nur-sabrina-ungku-abdul-nassir-55802318/'> Ungku Nur Sabrina Binti Ungku Abdul Nassir </a>", unsafe_allow_html=True)

# Interactive session

# Part1 : Store the totalAmount

st.write("Welcome to the RBA Car Loan Calculator.")

while True:

    totalAmount = input("Please enter the total amount.")
    try:
        totalAmount = int(totalAmount)
        break
    
    except ValueError:
        print("Please enter a number.")

# Part2 : Store the downPayment

while True:

    downPayment = input("Please enter the down payment.")
    try:
        downPayment = int(downPayment)
        break
    
    except ValueError:
       st.write("Please enter a number.")
    


# Part3 : Store the interestRate

while True:

    interestRate = input("Please enter the interest rate.")
    try:
        interestRate = float(interestRate)
        break
    
    except ValueError:
        st.write("Please enter a number.")
      
    
# Part4 : Store the loanPeriod

while True:

    loanPeriod = input("Please enter the loan period\n")
    try:
        loanPeriod = float(loanPeriod)
        break
    
    except ValueError:
        st.write("Please enter a number.")
        
