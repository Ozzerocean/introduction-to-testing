# Introduction-to-Testing
[HoneyRose](https://www.honeyroseusa.com/)

## Test case №1
Name: Adding an item to the bag

#### Preconditions

- Internet connection.
- Product page is opened.

#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | Choose _Quantity_ of the product | _Quantity_ is chosen     | _Quantity_ is chosen     |
| 2.    |    Click the _Add to Bag_ button                                         |     	The prodoct added to bag, appeared buttons _Add else_ and _Go to bag_. There is information about the product, quantity, total price in the bag                     |        The prodoct added to bag, appeared buttons _Add else_ and _Go to bag_. There is information about the product, quantity, total price, the button _Remove_ in the bag                |

## Test case №2
Name: Finding a store in your city

#### Preconditions

- Internet connection.
- Website https://www.honeyroseusa.com/ is opened.
- Allow/Not allow to show your location.

#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | Click on the button _Stores_  | _Location_ page is opened | _Location_ page is opened |
| 2.  | Click and select categories _Radius_ and input _city, state or zip_     | Information about store is showed     | Information about store is showed     |
| 3.    |     Click on the button _Search_          |     	Will be chosen the nearest store         |        Nothing happened, the button is provided in case the search does not happen automatically    |

## Test case №3
Name: Viewing _Main_ page  

#### Preconditions

- Internet connection.


#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | Open the site and close all popups in the way that content is clickable | Header top lings, logo image, header navigation bar, search, groups of the product, recomended products, footer navigation, footer copyright blocks are rendered |Header top lings, logo image, header navigation bar, search, groups of the product, recomended products, footer navigation, footer copyright blocks are rendered|

## Test case №4
Name: Product search

#### Preconditions

- Internet connection.
- Main page is opened.

#### Test Steps

| ID  | Test Step Description                       | Expected Output          | Actual Output            |
| --- | ------------------------------------------- | ------------------------ | ------------------------ |
| 1.  | Click on the picture _Search_, click on the search input and type askdkskdaaksdkakdk text | _No product found page_ is opened | _No product found page_ is opened and text _Sorry, no results_ is rendered |
| 2.  | Click on the picture _Search_, click on the search input and type _Cigarettes_ text| Product page is opened    | Product page is opened and result of search is displayed|

