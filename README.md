CHARLES-BOOK-CLUB RFM SEGMENTATION

Charles-Book_club is a case study extracted from, Data Mining for Business Analytics Concepts, Techniques and Applications in Python by Galit Shmueli Peter C. Bruce Peter Gedeck Nitin R. Patel (z-lib.org) textbook.

BACKGROUND

The Charles Book Club (CBC), a book club, that focuses on selling speciality books by direct marketing through variety of channels, including media advertising and email has created an active database of 500,000 readers. CBC is strictly a distributer and does not publish any of the books it sells.

PROBLEM

While CBC mailing volume and customer database was increasing with book selection diversifying and growing, their profits were decreasing. This led CBC to to deriving intelligence from their data to better know their customers and design targeted marketing strategies to their most profitable customers.


RFM SEGMENTATION

While the initial purpose of this analysis was to perform a k-NN and logistic regression on CharlesBookClub.csv, this analysis will focus more on a well known standard industry practice known as RFM (recency, frequency, monetary) segmentation.

R = recency, time since last purchase

F = frequency, number of previous purchases from the company over a period

M = monetary, amount of money spent on the company's product over a period.

The assumption is that the more recent the last purchase, the more products bought from the company in the past, and the more money spent in the past buying the company's products, the more likely the customer is to purchase the product offered.


RECENCY:

0-2 months (Rcode = 1)

3-6 months (Rcode = 2)

7-12 months (Rcode = 3)

13 months and up (Rcode = 4)


FREQUENCY:

1 book (Fcode = 1)

2 books (Fcode = 2)

3 books (Fcode = 3)


MONETARY:

$0-$25 (Mcode = 1)

$26-$50 (Mcode = 2)

$51-$100 (Mcode = 3)

$101-$200 (Mcode = 4)

$201 and up (Mcode = 5)
