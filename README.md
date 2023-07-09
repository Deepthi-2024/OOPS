# OOPS

A Car dealer wants to automate the billing process of cars based on the car selected. The customer has the option to choose below.

Car Model Cost(Showroom price)
Polo Trendline 8.70 lakh
Polo Highline 10.09 lakh
Virtus Trendline 11.05 lakh
Virtus Highline 13.08 lakh
Taigun Trendline 14.89 lakh
Taigun Highline 15.42 lakh
Taigun Topline 17.71 lakh

Once the customer has selected the car, additional taxes and fees have to be paid as given below

Fee type Cost
RTO 1,13,990
Insurance 47,300
TCS charges 11,000
Additional Accessories 15,000

 

In the additional section, customers have the option to opt-out for insurance and additional accessories.
The car dealer has the option to give a discount either in percentage or in rupees(A dealer discount has to be applied to the showroom price). Car dealers can apply a discount only if the customer opts in for either insurance or additional accessories and cannot cross 30,000. There should be an error saying the maximum discount to be applied should not cross 30,000 and only apply 30,000 as a discount.
If the customer doesn’t opt-in for insurance or additional accessories and if the dealer tries to add a discount it should show an error saying any one of the additional features has to be added and 0 discount has to be added.
After selecting the car and opt-in options the total amount to be paid has to be displayed

SAMPLE INPUT 1 :

Select car model: Virtus Highline
Do you need Insurance: yes
Do you need Additional Accessories: no
Dealer discount: 2%
Output: Total cost 14,54,130 (Virtus Highline 13,08,000 + 1,13,990(RTO) + 47,300(Insurance) + 11,000(TCS) - 26160(Dealer discount))


SAMPLE INPUT 2 :

Select car model: Taigun Topline
Do you need Insurance: yes
Do you need Additional Accessories: yes
Dealer discount: 20,000

Output: Total cost 19,38,290 (Taigun Topline 17,71,000 + 1,13,990(RTO) + 47,300(Insurance) + 11,000(TCS) + 15,000(Additional Accessories) - 20,000(Dealer discount))



SAMPLE INPUT 3:

Select car model: Polo Trendline
Do you need Insurance: no
Do you need Additional Accessories: no
Dealer discount: 0

Output: Total cost 9,94,990 (Polo Trendline 8,70,000 + 1,13,990(RTO) + 0(Insurance) + 11,000(TCS) + 0(Additional Accessories) - 0(Dealer discount))
