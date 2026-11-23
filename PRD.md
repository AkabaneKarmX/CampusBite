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

Reminds me of a time i was at BUSA and wanted to get food(The mixed rice) and i had to wait because most of the customers are
either girls or boys waiting to get the exact same food for their girlfriends. They were at least 15 in numbers and by the time
it got to my turn, they ran out

 3. Research

1. Who has the problem

Mostly students on busy lecture days, and the vendors who serve them at break times. Lecturers and staff probably buy food too but we haven't looked at them, so they are outside this for now.

2. How people deal with it now

From what we've seen and from talking to people,

a. Walk there, queue, and accept the wait
b. Ask a friend who is already close to the vendor to buy for them, then send the money by transfer
c. Call or WhatsApp the vendor to order in advance. This works until the vendor is too busy to reply (Sometimes you just can't reach them) 
d. Buy snacks or skip the meal

3. Why the current options don't work well enough

WhatsApp has no menu and no list of orders, and there's no way to tell what has run out. Plus i don't think there's really a 
delivery app that's actually on Babcock that's actually approved or not that i've seen one myself

4. Interviews and survey

We plan to speak to at least five students and two vendors, and send a short Google Form to course mates.

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

[To be filled in after the interviews, including anything that goes against our idea.]

a. Student 1 (200L, Computer Science): "..."
b. Vendor 1 (name of place): "..."
c. Survey: X responses, Y% said ...

 4. Business objectives

a. Reduce the time students spend waiting for food
b. Help vendors cope with the rush without losing orders
c. Get a few vendors and a decent number of students actually using it. A product nobody uses doesn't teach us anything
d. Find out if students or vendors would be willing to pay for it later

 5. Target users

1. "Students" order food. They want it to be quick and they want to know before walking over whether the food is available

2. "Vendors" run a food stall or counter. They want to see orders clearly and keep their menu up to date without much effort

3. "Administrators" manage the platform. They approve vendors and deal with complaints

A student here is only a buyer. Vendors get their own account type because what they need from the app is quite different

 6. Stakeholders

BUSA is the place on the Babcock campus where the vendors meet and where students go to buy food, snacks, ice cream and a lot of other things.

a. Our team (product owner): that it works and people use it
b. Babcock students: fast food at a fair price
c. BUSA vendors: more sales, fewer mix-ups
d. Babcock University management: rules about vending on campus, student welfare
e. Babcock cafeteria management: whether they'd take part, and how it affects them
f. Support (also us for now): handling complaints and reports

 7. Business goals and user needs

a. Get BUSA vendors on board: "I want to see my orders without shouting across the counter."
b. Get more orders: "I want to know the food is there before I walk."
c. Build trust: "I want my order to be ready when I arrive."
d. Fewer disputes: "I want proof of what I ordered."

Example of a need becoming a requirement: a student says "I want to know if the food is available before I walk there." The requirement is "The system shall show each menu item as available or sold out to logged-in students."

 8. User stories

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

 9. Functional requirements

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

 10. Non-functional requirements

a. Performance: menu pages should load in under 3 seconds on an average Babcock campus connection.
b. Security: passwords are hashed and never stored in plain text. Vendors can only see and change their own menu and orders.
c. Reliability: if a student taps "place order" twice or the network drops and retries, only one order should be created.
d. Availability: the app should be up during the hours vendors are open. We still need to agree on an actual uptime figure.
e. Scalability: it has to cope with the break-time rush. We'll set a number once we know how many vendors and students to expect.
f. Privacy: a student's name and phone number are only visible to the vendor handling that order.
g. Usability: it must work well on a phone browser, since that is what most Babcock students will use.

 11. Scope and priorities (MoSCoW)

Must have: registration and login, vendor menus, placing a pickup order, order status updates, vendor view of incoming orders.

Should have: sold-out toggle, cancelling an order, order history, reporting a problem, admin approval of vendors.

Could have: SMS or email notifications, vendor ratings, showing opening hours, ordering for a later time.

Won't have this time: online payments, delivery, loyalty points, recommendations, support for any campus other than Babcock.

 12. The MVP

Right now, students can only order by walking up to a vendor at BUSA. The first version only needs to prove that a Babcock student can order and collect food from a BUSA vendor without standing in a queue. It includes:

1. Student and vendor registration and login
2. Vendor menu management
3. Students browsing menus and placing a pickup order
4. Vendors seeing orders and updating their status
5. Students seeing the status of their order
6. Basic admin approval of vendors

Payment is not part of the MVP. Students pay at pickup, by cash or transfer, the same way they do now. We don't want to handle people's money before we know anyone wants to use the app.

There are a lot of vendors at BUSA, so for the pilot we'd start with [one or two] of them and a small group of students, see what breaks, then widen it.

 13. Acceptance criteria

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

[Criteria for the remaining requirements to be added before submission.]

14. Success metrics

a. Registered students and approved vendors
b. Orders placed per week
c. Share of orders completed rather than cancelled or rejected
d. Average time between an order being placed and being ready
e. Students who come back and order more than once
f. Problems reported

 15. Assumptions

None of these are confirmed yet:

a. BUSA vendors have a smartphone or some device they can keep at the stall.
b. The internet at Babcock is good enough to use between classes.
c. Babcock University is fine with this kind of platform for campus vendors.
d. Students are happy to pay at pickup, by cash or transfer.

 16. Open questions

1. Will BUSA vendors take part, and what would persuade them?
2. Do we need permission from Babcock University, the cafeteria management or whoever runs BUSA? We don't know yet.
3. How do we check that someone is a Babcock student (school email, matric number, something else)?
4. Who is responsible when an order is wrong or never collected?
5. Will we ever handle payments, and how?
6. What do we do with orders nobody comes to pick up?
7. How many orders can one vendor actually handle at peak time?

 17. Risks

a. BUSA vendors may not want to use it. We start with one friendly vendor and keep the vendor side as simple as possible.
b. Students may order and not show up. Vendors should be able to report no-shows, and we can think about limits later.
c. Campus internet may be poor, so pages should stay light.
d. Vendors may forget to mark things sold out, so that toggle should take one tap.

 18. What comes next

Week 5 is architecture and technology choices. Nothing above depends on a particular language or framework.