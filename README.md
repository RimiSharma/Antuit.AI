# Antuit.AI

Here I have solved the coding challenge for Antuit.AI

# Coding problem statement:

Find the dataset for a forecasting challenge.

The goal is to forecast the requested_qty amounts for the month of June and July in 2020. Currently the sell_in_qty and requested_qty for these two months are null.

Here is the product hierarchy levels:

 

Business Unit

|

|__ Business Group

                |

                |__ Major Product Group

                                |

                                |__ Product Group

                                                |

                                                |__ Lineage

                                                                |

                                                                |__ product_id

 

 

Please submit your python code in form of an ipython notebook and its html export.

Add your justification, reasoning, and commentary in the notebook. Please also attach a word file to add more detailsand descriptions.

# Solution

In order to forecast the requested quantity amount and sell in quantity amount, I used Long Short-term Memory (LSTM) method which is a popular tool in Deep Learning. In order to implement LSTM I used Keras.

The predicted value for requested quantity are - 

June - 616150.0

July - 293471.0

The prdicted value for sales in quantity are -

June - 530704.0

July - 126409.0


