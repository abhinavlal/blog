+++
categories = []
date = "2018-07-02T17:32:54+00:00"
draft = true
tags = []
title = "Paytm Analytics"

+++
As i recharged by paytm wallet for the nth time i asked myself where am i spending on paytm. How much recharge i do every month ? How much cashback does paytm actually provide ?

As i looked through Paytm app and website i could not find anything to answer these questions. Next i went looking for Paytm API but again i could not find one. Next i looked at API call being made on wallet transactions page and the pattern seemed simple enough. Then i wrote a quick and dirty python script to export paytm transaction data as CSV.

After that i imported CSV file in google data studio to analyze the data and get answers to my simple questions. Next you can setup a simple cron to export this data 