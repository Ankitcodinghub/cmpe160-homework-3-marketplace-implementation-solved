# cmpe160-homework-3-marketplace-implementation-solved
**TO GET THIS SOLUTION VISIT:** [CMPE160 Homework 3-Marketplace Implementation Solved](https://www.ankitcodinghub.com/product/cmpe160-homework-3-marketplace-implementation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93983&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPE160 Homework 3-Marketplace Implementation Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

<ol>
<li>Introduction:
Economy is an indispensable fact of our lives. In real life, for buying and selling things, we use some printed or virtual assets, called money. However, your money does not have any difference with paper in your pocket. It gains its value only in a marketplace.

In this project, you are going to implement a basic marketplace model. This model consists of traders, wallets, transactions, currencies, and the market. For simplicity we have two currencies in the market: dollar and PQoin (Priority Queue Coin). Traders can give buying or selling orders to the market, if they can afford.

In our market model, there are two priority queues for storing orders. In a priority queue, elements having highest priority serve before. The priority rules are written in the next sections. With these rules, your market implementation should make transactions if these two priority queues’ tops overlap.

We are expecting from your code, to give proper outputs for given inputs.
</li>
<li>Packages &amp; Classes:
You are provided with the general structure of the project below. In this context, there are 2 packages and 8 classes. The details of the classes, functionalities to be implemented and overall operations of the project with the corresponding format are presented in the following sections.
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.1.

</div>
<div class="column">
Package: executable

The java files of these classes are currently empty, you need to implement

these classes according to the information provided in this document.

2.1.1. Main.java

The Main class should be implemented in a way that it should read corresponding parameters and events from the input file, and log the results to the output file. The input and output file paths are given in arguments of the program.

You should create a random object with the given seed. In order to access Random object everywhere, you may define it as a static object:

public static Random myRandom;

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
2.2.

</div>
<div class="column">
Package: elements

The java files of these classes are currently empty, you need to implement these classes according to the information provided in this document.

<ol>
<li>2.2.1. &nbsp;Market.java
There is only one market throughout the program.

The fields and methods to be implemented in Market.java:

private PriorityQueue&lt;SellingOrder&gt; sellingOrders; private PriorityQueue&lt;BuyingOrder&gt; buyingOrders; private ArrayList&lt;Transaction&gt; transactions; public void giveSellOrder(SellingOrder order); public void giveBuyOrder(BuyingOrder order); public void makeOpenMarketOperation(double price); public void checkTransactions(ArrayList&lt;Trader&gt; traders);

public Market(int fee);

The additional data for implementing these methods are given in the “Implementation Details” section.
</li>
<li>2.2.2. &nbsp;Order.java
Order is the parent class of BuyingOrder.java and SellingOrder.java. Every Order should have:

double amount;

double price;

int traderID;

public Order(int traderID, double amount, double price)
</li>
<li>2.2.3. &nbsp;SellingOrder.java
SellingOrder.java should be a child of Order.java.

In order to implement PriorityQueue&lt;SellingOrder&gt;, the SellingOrder method implements Comparable, and compareTo(SellingOrder e) should be overridden. The comparison logic of SellingOrder is given in “implementation details” in this document.
</li>
<li>2.2.4. &nbsp;BuyingOrder.java
BuyingOrder.java should be a child of Order.java.

In order to implement PriorityQueue&lt;BuyingOrder&gt;, the BuyingOrder method implements Comparable, and compareTo(BuyingOrder e) should be overridden. The comparison logic of BuyingOrder is given in “implementation details” in this document.
</li>
<li>2.2.5. &nbsp;Trader.java
Each Trader object created in the program has an ID and a wallet. The IDs of the traders are starting from 0 and incremented when a trader object is created. A trader can give buying or selling orders into the market. However if the trader cannot afford that order, there is nothing to do.
</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
The fields and signature of the methods that should be implemented for the Trader class are as follows:

private int id;

private Wallet wallet;

public Trader(double dollars, double coins); public int sell(double amount, double price, Market market);

public int buy(double amount, double price, Market market);

public static int numberOfUsers = 0;

<ol start="6">
<li>2.2.6. &nbsp;Wallet.java
Each Wallet object keeps the amounts of dollars and PQoins.

The necessary fields and signature of the methods to be implemented for the Wallet class are as follows:

private double dollars;

private double coins;

private double blockedDollars;

private double blockedCoins;

public Wallet(double dollars, double coins);
</li>
<li>2.2.7. &nbsp;Transaction.java
Each Transaction object includes a buying and a selling order.

private SellingOrder sellingOrder; private BuyingOrder sellingOrder;
</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
3. Implementation Details:

★ PriorityQueue functionality in the Market:

<ul>
<li>○ &nbsp;There are two distinct PriorityQueue you have. One of them is for
SellingOrders, the other is for BuyingOrders.
</li>
<li>○ &nbsp;PriorityQueue&lt;SellingOrder&gt;</li>
</ul>
■ When you poll() this PQ you should get the SellingOrder that has the lowest price. If two orders have the same price then you get the SellingOrder which has the highest amount. If it is still the same, you get the SellingOrder that has the lowest tradersID.

○ PriorityQueue&lt;BuyingOrder&gt;

■ When you poll() this PQ you should get the BuyingOrder that has the

highest price. If two orders have the same price then you get the BuyingOrder which has the highest amount. If it is still the same, you get the BuyingOrder that has the lowest tradersID.

○ At the end of each query, the market checks whether the prices at the PQs are overlapping. If there is an overlap, the market should make transactions with the top of PQs, until there is no overlapping.

<ul>
<li>★ &nbsp;Query#666 (make open market operation):
<ul>
<li>○ &nbsp;In this query, Trader#0 (The System) gives buying or selling orders for setting
the current price of PQoin to the given price.
</li>
<li>○ &nbsp;The final price can differ from the given price. The market tries to converge as
much as possible.
</li>
<li>○ &nbsp;You should create system’s orders until:
■ priceofbuyingOrders.peek()&lt;pricegivenbythe system

■ priceofsellingOrders.peek()&gt;pricegivenbythe system
</li>
</ul>
</li>
<li>★ &nbsp;Handling Orders:
<ul>
<li>○ &nbsp;After a BuyingOrder is given, dollars reserved for this order (amount*price)
cannot be used again. Therefore, you should store this amount in the

blockedDollars of the trader’s wallet.
</li>
<li>○ &nbsp;After a SellingOrder is given, PQoins reserved for this order (amount) cannot
be used again. Therefore, you should store this amount in the blockedCoins

of the trader’s wallet.
</li>
<li>○ &nbsp;When making transactions the blocked currencies should disappear.</li>
<li>○ &nbsp;When making transactions the amount of BuyingOrder and the amount of
SellingOrder are possibly different. In that case you should divide an order into two parts. One goes to transaction, the other returns back to its PriorityQueue.
</li>
<li>○ &nbsp;When making transactions the price of BuyingOrder and the price of Selling order might differ. If so, you should take the SellingOrder’s price as the Transaction price. However if this is the case, the amount of dollars blocked for extra price should return to the wallet.</li>
</ul>
</li>
<li>★ &nbsp;Market Fee:
<ul>
<li>○ &nbsp;The market fee is an integer representing how much commission the market
recieve from the transaction per thousand.
</li>
<li>○ &nbsp;Conducting a transaction, Seller gets (amount*price*(1-fee/1000).</li>
</ul>
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
4. Input &amp; Output:

</div>
</div>
<div class="layoutArea">
<div class="column">
The first line of the input file specifies the random seed that you have to use to generate random numbers in the project.: A

The second line of the input file specifies the initial transaction fee of the marketplace, the number of users ,and number of queries: B C D

The next C lines represent the initial dollars and PQoins asset in each trader’s wallet.

&lt;dollar_amount&gt; &lt;PQoin_amount&gt;

&lt;dollar_amount&gt; &lt;PQoin_amount&gt;

…

&lt;dollar_amount&gt; &lt;PQoin_amount&gt;

&lt;dollar_amount&gt; &lt;PQoin_amount&gt;

The next D lines are the queries. There are exactly 14 types of events.

Trader specific queries:

➔ 10: give buying order of specific price:

10 &lt;trader_id&gt; &lt;price&gt; &lt;amount&gt; Example: 10 1 3 34

Trader#1 tries to give a buying order for 34 PQoin with 3*34 dollars.

➔ 11: give buying order of market price: 11 &lt;trader_id&gt; &lt;amount&gt;

Example: 11 1 34

Trader#1 tries to give a buying order for the cheapest 34 PQoin order in the

market.

Note: This is similar to Query#10, but it takes the current selling price as price.

Note: If there is no current selling price then increment the number of invalid queries.

➔ 20: give selling order of specific price:

20 &lt;trader_id&gt; &lt;price&gt; &lt;amount&gt;

Example: 20 1 3 34

Trader#1 tries to give a selling order with 34 PQoin with 3 dollars for each.

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
<ul>
<li>➔ &nbsp;21: give selling order of market price: 21 &lt;trader_id&gt; &lt;amount&gt;
Example: 21 1 34

Trader#1 tries to give a selling order for the most expensive 34 PQoin order in the market.

Note: This is similar to Query#20, but it takes the current buying price as price.
</li>
<li>➔ &nbsp;3: deposit a certain amount of dollars to wallet: 3 &lt;trader_id&gt; &lt;amount&gt;
Example: 3 1 43

Trader#1 deposits 43 dollars to wallet#1.
</li>
<li>➔ &nbsp;4: withdraw a certain amount of dollars from wallet: 4 &lt;trader_id&gt; &lt;amount&gt;
Example: 4 1 43

Trader#1 withdraws 43 dollars from wallet#1
</li>
<li>➔ &nbsp;5: print wallet status:
5 &lt;trader_id&gt;

Prints “Trader &lt;traderID&gt;: &lt;trader_s_dollars&gt;$ &lt;trader_s_PQoins&gt;PQ” Example:

Trader 5: 34.0$ 23.0PQ

System queries:
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
➔

➔

</div>
<div class="column">
777: give rewards to all traders:

777

When this query is read, the system creates and distributes random amounts of PQoins to all traders.

for each trader add

myRandom.nextDouble()*10

coins to the trader’s wallet.

666: make open market operation:

666 &lt;price&gt;

</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
➔

➔

➔

➔

➔

</div>
<div class="column">
When this query is read, the system compensates buying or selling orders in order to set the price of PQoin to the given price.

This query can increase or decrease the total amount of PQoin in the market.

500: print the current market size:

500

Prints “Current market size: &lt;total_$_in_buying_pq&gt; &lt;total_PQoin_in_selling_pq&gt;” to the output file.

501: print number of successful transactions:

501

Prints “Number of successful transactions: &lt;num_of_successful_transaction&gt;” to the output file.

502: print the number of invalid queries:

502

Prints &lt;number_of_invalid_queries&gt; to the output file.

Note: If a trader is unable to satisfy the query’s liabilities, then the number of invalid queries is incremented by one.

505: print the current prices:

505

Prints;

“Current prices: &lt;cp_buying&gt; &lt;cp_selling&gt; &lt;cp_average&gt;

to the output file.

Note: if one of the PriorityQueues is empty then the price related to it, is not included in the average current price.

555: print all traders’ wallet status

555

Prints “&lt;trader_s_dollars&gt;$ &lt;trader_s_PQoins&gt;PQ” of all traders.

</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
5. Important Remarks:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>● &nbsp;The method signatures and field names should be exactly the same with the ones specified in this document.</li>
<li>● &nbsp;You can implement and utilize additional helper methods of your choice.</li>
<li>● &nbsp;You should implement getters and setters, if it is necessary.</li>
<li>● &nbsp;Please keep in mind that providing the necessary accessibility and visibility is
important: you should not implement everything as public, even though the necessary functionality is implemented. The usage of appropriate access modifiers and other Java keywords (super, final, static etc.) play an important role in this project since there will be partial credit specifically for the software design.
</li>
<li>● &nbsp;You should document your code in Javadoc style including the class implementations, method definitions (including the parameters and return if available etc.), and field declarations. You are not going to submit a documentation file generated by Javadoc.</li>
<li>● &nbsp;You may use Java’s PriorityQueue classes as well as you may implement yours.</li>
<li>● &nbsp;Do not make assumptions about the numbers and the size of the input.</li>
<li>● &nbsp;All amounts and prices are given in float.</li>
<li>● &nbsp;The current price is calculated:
<ul>
<li>○ &nbsp;the top of selling priority queue when buying from the market</li>
<li>○ &nbsp;the top of buying priority queue when selling from the market</li>
<li>○ &nbsp;the average of the tops of buying and selling priority queues when the system
prints the current price. If one of the PriorityQueues is empty then the price

related to it, is not included in the average current price.
</li>
</ul>
</li>
<li>● &nbsp;Trader#0 is reserved for the system. If you test the code without awareness of this,
your output can differ from what you expect.
</li>
<li>● &nbsp;Do not forget to use the given random seed.</li>
<li>● &nbsp;If a trader does not have enough assets for buying, selling, or withdrawing, the
number of invalid queries increases.
</li>
</ul>
</div>
</div>
</div>
</div>
