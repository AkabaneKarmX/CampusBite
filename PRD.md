CampusBite PRD

BU-209 Backend Engineering, Week 4
Team: Group 5
Date: 23/11/2026

---

1. Product overview

CampusBite is a web app where students order food from campus vendors before they get there, then pick it up when it's ready. Vendors use the same app to see what has been ordered and to say when something is finished.

2. Problem statement

Students have a short gap between lectures, sometimes less than an hour. A good part of it goes on standing in line for food, and by the time you get to the front the thing you wanted is sometimes finished. Then you either settle for something else or go to class hungry.

The vendors have a different version of the same problem. Everyone shows up at the same time, orders are shouted across and mistakes happen. Some vendors take orders on WhatsApp, but when they're busy serving they can't keep up with messages.

Reminds me of a time i was at BUSA and wanted to get food(The mixed rice) and i had to wait because most of the customers are either girls or boys waiting to get the exact same food for their girlfriends. They were at least 15 in numbers and by the time it got to my turn, they ran out

2.1 Who has the problem

Mostly students on busy lecture days, and the vendors who serve them at break times. Lecturers and staff probably buy food too but we haven't looked at them, so they are outside this for now.

2.2 How people deal with it now

From what we've seen and from talking to people,

a. Walk there, queue, and accept the wait
b. Ask a friend who is already close to the vendor to buy for them, then send the money by transfer
c. Call or WhatsApp the vendor to order in advance. This works until the vendor is too busy to reply (Sometimes you just can't reach them)
d. Buy snacks or skip the meal

2.3 Why the current options don't work well enough

WhatsApp has no menu and no list of orders, and there's no way to tell what has run out. Plus i don't think there's really a delivery app that's actually on Babcock that's actually approved or not that i've seen one myself

2.4 Interviews and survey

We spoke to seven students and two vendors, and sent a short Google Form to course mates.

Questions we asked the students were

1. How often do you buy food on campus on a normal lecture day?
2. How long do you usually wait, and has it ever made you late?
3. How do you decide where to eat?
4. Have you gone to a vendor and found the food finished?
5. Would you pay a small extra fee to skip the queue?
6. Would you rather pay online or at pickup?

Questions we asked the vendors

1. When are your busiest hours?
2. How do you take and keep track of orders now?
3. Do people call or WhatsApp you to order? How do you manage that?
4. Do you have a smartphone or laptop at the stall?
5. What would make you not want to use an app like this?

What people told us:

a. Student 1 (200L): "The queue can be crazy sometimes, especially between lecture periods. You can end up spending most of your break trying to buy food."

b. Student 2 (100L): "I mostly choose where to eat based on the price and what I'm craving. If somewhere is too crowded, I'll just go somewhere else."

c. Student 3 (300L): "I've gone to buy food before and found out it had finished. It's annoying, especially when that's what you came for."

d. Student 4 (200L): "Ordering before getting there would actually be nice. At least you won't have to waste time standing in a queue."

e. Student 5 (100L): "I don't really mind waiting if the food is worth it. I don't think I'd pay extra just to skip the queue."

f. Student 6 (200L): "It would be convenient, but the ordering process has to be easy. Nobody wants another stressful thing to deal with."

g. Student 7 (300L): "I'd rather pay when I get my food. I'm not really comfortable paying online before collecting it."

h. Vendor 1 (BUSA food stall, mixed rice): "Between 12 and 1, I can't even look at my phone. Everybody is talking at once, some are asking the price, some are saying 'the one I ordered'. I write the orders on paper but by the time the rush finishes the paper is a mess. If orders just came in on a screen in order, it would be easier for me and I won't forget anybody."

i. Vendor 2 (snacks and drinks stand): "My regulars message me on WhatsApp to keep their things aside. The problem is when I'm attending to customers I don't see the message until they're already here. And sometimes two people want the same last bottle. If the app tells me before they come, I can keep it aside properly."

j. Survey: 26 course mates replied. 81% buy food on campus at least three times a week. 69% have waited more than 15 minutes at BUSA in one break, and 58% have walked to a vendor and found the food finished. 46% have been late to a lecture or missed one because of the queue. 62% would use an app that lets them order ahead and pay at pickup. 15% would pay an extra fee. 12 of the 26 already try to order ahead on WhatsApp.

3. Business objectives

a. Reduce the time students spend waiting for food
b. Help vendors cope with the rush without losing orders
c. Get a few vendors and a decent number of students actually using it. A product nobody uses doesn't teach us anything
d. Find out if students or vendors would be willing to pay for it later

3.1 Business goals

a. Get BUSA vendors on board: "I want to see my orders without shouting across the counter."
b. Get more orders: "I want to know the food is there before I walk."
c. Build trust: "I want my order to be ready when I arrive."
d. Fewer disputes: "I want proof of what I ordered."

3.2 User needs

Take one need from above. A student says "I want to know if the food is available before I walk there." That turns into "The system shall show each menu item as available or sold out to logged-in students."

3.3 Success metrics

a. Registered students and approved vendors
b. Orders placed per week
c. Share of orders completed rather than cancelled or rejected
d. Average time between an order being placed and being ready
e. Students who come back and order more than once
f. Problems reported

4. Target users

1. "Students" order food. They want it to be quick and they want to know before walking over whether the food is available

2. "Vendors" run a food stall or counter. They want to see orders clearly and keep their menu up to date without much effort

3. "Administrators" manage the platform. They approve vendors and deal with complaints

A student here is only a buyer. Vendors get their own account type because what they need from the app is quite different

5. Stakeholders

BUSA is the place on the Babcock campus where the vendors meet and where students go to buy food, snacks, ice cream and a lot of other things.

a. Our team (product owner): that it works and people use it
b. Babcock students: fast food at a fair price
c. BUSA vendors: more sales, fewer mix-ups
d. Babcock University management: rules about vending on campus, student welfare
e. Babcock cafeteria management: whether they'd take part, and how it affects them
f. Support (also us for now): handling complaints and reports

6. User stories

Student:

a. As a student, I want to create an account so that I can place orders.
b. As a student, I want to see which vendors are open so that I know where to order from.
c. As a student, I want to see a vendor's menu and prices so that I can decide what to buy.
d. As a student, I want to place an order for pickup so that I don't have to queue.
e. As a student, I want to see my order status so that I know when to go and collect it.
f. As a student, I want to cancel an order the vendor hasn't accepted yet so that I'm not stuck with food I no longer want.

Vendor:

a. As a vendor, I want to add and edit my menu so that students can see what I sell.
b. As a vendor, I want to mark an item as sold out so that students stop ordering it.
c. As a vendor, I want to see new orders as they come in so that I can prepare them.
d. As a vendor, I want to mark an order as ready so that the student knows to come.

Administrator:

a. As an admin, I want to approve vendor accounts so that only real BUSA vendors are listed.
b. As an admin, I want to see reported problems so that I can act on them.

7. Functional requirements

a. FR-01: Students can register and log in.
b. FR-02: Vendors can register and log in. An admin must approve the account before it goes live.
c. FR-03: Vendors can add, edit and remove menu items (name, price, description, optional photo).
d. FR-04: Vendors can mark an item as available or sold out.
e. FR-05: Students can browse approved vendors.
f. FR-06: Students can view a vendor's menu.
g. FR-07: Students can add items to an order and submit it.
h. FR-08: Vendors can see incoming orders and accept or reject them.
i. FR-09: Vendors can update an order's status.
j. FR-10: Students can see the current status of their orders.
k. FR-11: Students can cancel an order before the vendor accepts it.
l. FR-12: Students can view their past orders.
m. FR-13: Users can report a problem with an order or a vendor.
n. FR-14: Admins can approve or suspend vendors and review reports.

8. Non-functional requirements

a. Performance: menu pages should load in under 3 seconds on an average Babcock campus connection.
b. Security: passwords are hashed and never stored in plain text. Vendors can only see and change their own menu and orders.
c. Reliability: if a student taps "place order" twice or the network drops and retries, only one order should be created.
d. Availability: the app should be up during the hours vendors are open. We still need to agree on an actual uptime figure.
e. Scalability: it has to cope with the break-time rush. We'll set a number once we know how many vendors and students to expect.
f. Privacy: a student's name and phone number are only visible to the vendor handling that order.
g. Usability: it must work well on a phone browser, since that is what most Babcock students will use.

9. Scope and priorities

Prioritised with MoSCoW:

Must have: registration and login, vendor menus, placing a pickup order, order status updates, vendor view of incoming orders.

Should have: sold-out toggle, cancelling an order, order history, reporting a problem, admin approval of vendors.

Could have: SMS or email notifications, vendor ratings, showing opening hours, ordering for a later time.

Won't have this time: online payments, delivery, loyalty points, recommendations, support for any campus other than Babcock.

9.1 The MVP

Right now, students can only order by walking up to a vendor at BUSA. The first version only needs to prove that a Babcock student can order and collect food from a BUSA vendor without standing in a queue. It includes:

1. Student and vendor registration and login
2. Vendor menu management.
3. Students browsing menus and placing a pickup order
4. Vendors seeing orders and updating their status
5. Students seeing the status of their order
6. Basic admin approval of vendors

Payment is not part of the MVP. Students pay at pickup, by cash or transfer, the same way they do now. We don't want to handle people's money before we know anyone wants to use the app.

There are a lot of vendors at BUSA, so for the pilot we'd start with two of them and a small group of students, see what breaks, then widen it.

10. Acceptance criteria

Place an order (FR-07)

a. The student must be logged in.
b. The order must have at least one item.
c. All items must come from the same vendor.
d. Items marked sold out can't be added.
e. Quantity must be a whole number greater than zero.
f. A successful order is saved with status "pending" and the student sees a confirmation.
g. An invalid order is rejected with a clear error message.
h. Submitting the same order twice doesn't create a duplicate.

Add a menu item (FR-03)

a. The vendor must be logged in and approved.
b. Name and price are required.
c. Price must be greater than zero.
d. The photo is optional.
e. A vendor can only edit items on their own menu.

Update order status (FR-09)

a. Only the vendor who owns the order can change its status.
b. Status moves forward only: pending, accepted, preparing, ready, collected. A vendor can reject an order while it is still pending.
c. The student sees the new status once it changes.

Register and log in (FR-01)

a. A student registers with a name, phone number, email and password.
b. An email can only be registered once.
c. The password must be at least eight characters and is hashed before it is saved.
d. A wrong password and an unknown email both return the same error message.
e. A logged-in user stays logged in until they log out or the session expires.

Vendor registration (FR-02)

a. A vendor registers with a stall name, owner name, phone number and password.
b. The account is saved as "pending" and cannot go live without an admin.
c. A pending vendor can log in but cannot add menu items or receive orders.
d. A rejected vendor sees the reason on their dashboard.
e. Only an admin can change a vendor's approval status.

Mark an item sold out (FR-04)

a. The vendor must be logged in and approved.
b. One tap changes the item's state and saves it.
c. Sold-out items stay on the menu and show as sold out.
d. A student can't add a sold-out item to an order.
e. The change is visible to students the next time the menu loads.

Browse vendors (FR-05)

a. Only approved vendors appear in the list.
b. A suspended vendor disappears from the list.
c. Each entry shows the stall name and whether the vendor is accepting orders.
d. A student who is not logged in is sent to the login page.

View a menu (FR-06)

a. The menu shows each item's name, price and availability.
b. An item with no photo shows a placeholder image.
c. A sold-out item is visible but cannot be selected.
d. An empty menu shows a message instead of a blank page.

See incoming orders (FR-08)

a. A new order appears on the vendor's screen within a few seconds, with no refresh.
b. Orders are listed oldest first.
c. Each order shows the items, quantities, student name and total.
d. The vendor sees only orders placed with their own stall.
e. The vendor can accept or reject an order while it is pending.
f. Rejecting an order requires a reason, and the student sees it.

See order status (FR-10)

a. The student sees the status of their own orders only.
b. The status updates when the vendor changes it, with no refresh.
c. The status shown is always one of: pending, accepted, preparing, ready, collected, cancelled, rejected.

Cancel an order (FR-11)

a. A student can cancel only their own order.
b. Cancelling is allowed only while the order is pending.
c. A cancelled order leaves the vendor's queue.
d. The student sees a confirmation and the status changes to "cancelled".

View past orders (FR-12)

a. The student sees only their own orders.
b. Orders are listed newest first.
c. Each entry shows the date, vendor, items, total and final status.
d. Order history is read-only.

Report a problem (FR-13)

a. A student or vendor can report a problem from an order, or about a vendor.
b. A report needs a reason and an optional description.
c. The report saves the reporter, the order or vendor it refers to, and the time.
d. The reporter sees a confirmation after submitting.
e. The report appears on the admin's list.

Admin review (FR-14)

a. Only an admin can see pending vendors and open reports.
b. The admin can approve or reject a pending vendor, or suspend an approved one.
c. A suspended vendor's menu is hidden and the vendor cannot accept new orders.
d. Orders already accepted by a suspended vendor stay visible to the student.
e. Each admin action records which admin did it and when.

11. Assumptions and open questions

11.1 Assumptions

None of these are confirmed yet:

a. BUSA vendors have a smartphone or some device they can keep at the stall.
b. The internet at Babcock is good enough to use between classes.
c. Babcock University is fine with this kind of platform for campus vendors.
d. Students are happy to pay at pickup, by cash or transfer.

11.2 Open questions

1. Will BUSA vendors take part, and what would persuade them?
2. Do we need permission from Babcock University, the cafeteria management or whoever runs BUSA? We don't know yet.
3. How do we check that someone is a Babcock student (school email, matric number, something else)?
4. Who is responsible when an order is wrong or never collected?
5. Will we ever handle payments, and how?
6. What do we do with orders nobody comes to pick up?
7. How many orders can one vendor actually handle at peak time?

11.3 Risks

a. BUSA vendors may not want to use it. We start with one friendly vendor and keep the vendor side as simple as possible.
b. Students may order and not show up. Vendors should be able to report no-shows, and we can think about limits later.
c. Campus internet may be poor, so pages should stay light.
d. Vendors may forget to mark things sold out, so that toggle should take one tap.

What comes next

Week 5 is architecture and technology choices. Nothing above depends on a particular language or framework.
