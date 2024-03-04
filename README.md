<h1><b>Marketing Expense Optimization Project</h1></b>

Business Analytics

## Project Description

To understand business analytics, I have been offered a project in the analytical department at Yandex.Afisha.
The task is to help opitimize marketing expenses.

For the execution of this task, I have been granted access to resources that include:

- A comprehensive collection of server logs containing visitor data related to Yandex.Afisha, spanning the period from June 2017 through May 2018.
- A meticulously curated dump file encompassing a complete record of all transactions conducted during the specified timeframe.
- Statistics on the company's marketing expenditure.

<p></p>

The scope of my responsibilities within this project encompasses a comprehensive study of the following crucial areas:

- An in-depth analysis of user behavior, with a particular emphasis on understanding the manner in which individuals engage with our product.
- The precise identification of customer acquisition timelines, specifically focused on pinpointing the juncture at which they initiate their purchasing activities.
- The meticulous calculation of the financial contribution made by each individual customer.
- A thorough examination of the period within which customers successfully recoup their expenses.

<p></p>

This project's opportunity represents a significant step in refining the efficiency and cost-effectiveness of Yandex.Afisha's marketing endeavors.

<br></br>

## Data Dictionary

The <code>visits</code> table (server logs with data on website visits):

- <code>Uid</code>: user's unique identifier
- <code>Device</code> — user's device
- <code>Start Ts</code>: session start date and time
- <code>End Ts</code>: session end date and time
- <code>Source Id</code>: identifier of the ad source the user came from
  All dates in this table are in YYYY-MM-DD format.

The <code>orders</code> table (data on orders):

- <code>Uid</code>: unique identifier of the user making an order
- <code>Buy Ts</code>: order date and time
- <code>Revenue</code>: Yandex.Afisha's revenue from the order

The <code>costs</code> table (data on marketing expenses):

- <code>source_id</code>: ad source identifier
- <code>dt</code>: date
- <code>costs</code>: expenses on this ad source on this day
