# Bank User Manager (Bank Application)

## Overview

Bank User Manager is an *interactive system control* programme designed to assist banks in managing their customers'
information and providing fast and reliable financial services such as transactions, deposits, and withdrawals.

So, *why* should you use Bank User Manager?

1. For starters, it enhances the digital control efficiency of a bank system.
2. Second, it improves the security with which customers' information is managed.
3. Third, it facilitates financial operations.

## Goals

The *purpose* of this application is to provide **digital control flexibility** over a bank system, specifically to
assist bank employees:

- in better managing their customer information,
- to improve their client service, and
- to make banking transactions easier.

## Usages

The following ***user stories*** are all supported in GUI:

- As a user, I want to be able to create and add a new customer to the list of customers.
- As a user, I want to be able to select and view an existing customer’ info in the list of customers.
- As a user, I want to be able to edit a customer info in the list of customers.
- As a user, I want to be able to perform simple financial operations on a customer in the list of customers, such as
  deposit, withdraw and transfer.
- As a user, I want to be able to save my bank information to file.
- As a user, I want to be able to be able to load my bank information from file.
- As a user, I want to be able to add multiple Customer to Bank.

## Credits

- Created by Andrew Chen, andrewchenubc2021@gmail.com

I decided to make this application because there is a growing understanding in today's competitive industries, such as
banks, of the importance of promoting outstanding customer service, as it is critical in deciding a business's
reputation and its own vigour. Therefore, establishing a favorable connection with clients through effective customer
service will greatly improve a company's professional image.

## Citation

- Paul Carter, (Oct 16, 2021) JsonSerializationDemo (Version 20210307) [Source code]
  . https://github.students.cs.ubc.ca/CPSC210/JsonSerializationDemo.git
- Felix Grund, (Aug 9, 2021) TellerApp [Source code]. https://github.students.cs.ubc.ca/CPSC210/TellerApp.git
- Paul Carter, (Oct 21, 2021), AlarmSystem [Source code]. https://github.students.cs.ubc.ca/CPSC210/AlarmSystem.git

## Phase 4: Task 2

- As the user save and load the customers' information to and from file, events are logged.
- As the user edit customers information, events are logged.
- As the user perform transaction, deposit and withdrawal events are logged.
- As the user quits the application, all events are logged and printed.
- An image of representative sample of the event logs that occur when the program runs is included in the root.

## Phase 4: Task 3

- There are several duplicate codes in the abstract tab class that might be refactored out using the design patterns we
  learnt in this course, where it is critical to adhere to design principles in order to achieve software qualities
  such as maintainability and readability. For instance, my Tab abstract class has too many responsibilities that would
  have been better split into different classes to maintain cohesion. Similarly, the collaboration between my classes
  would have resulted in some design flow and high coupling that could have been improved by reducing the dependencies
  and method calls among them. The overall design architecture is preserved, however there is room for improvement.
