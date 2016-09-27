# referrals
An open-source referral program platform

## Use Cases

__User Roles:__ application, customer, administrator

 * `Application` can ask `system` whether a `customer` has been invited to the `application`
 * `Administrator` can start a `program`
 * `Administrator` can register `application` with the `program`
 * `Administrator` can add any `customers` to the program by entering their email addresses and creating their invitations immediately
 * Any `customer` with an invitation can directly start using the `application` upon clicking on the invitation link
 * Each `customer` has a certain number of allowed invitations, this means how many other `customers` they can invite. 
 * No `customer` can be invited twice, when a `customer` is already invited, whoever tries to invite them is notified
 * Inviting an already invited `customer` does not decrease the number of allowed invitations
 * The first activation of an invitation is tracked including date, time and geo-location from where the click came
 * `Administrator` can search for `customers` by date fo their activation, by date of their subscription to the waiting list, by the number of invitations sent, by the number of allowed invitations, by the number of invitations they can still send
 * `Customers` can register on a waiting list
 * `Administrator` can invite any number of `customers` from the waiting list setting how many allowed invitations they will have
 * `Administrator` can change the number of allowed remaining invitations to any `customer` or selected `customers` in a batch (i.e. ensure the minimal number of allowed invitations yet to be sent)
 * `Administrator` can search for invitations and sort/filter them by the date when they were sent, whether they have been activated, when they have been activated, where they have been activated
 * `Administrator` can create a report with charts showing a summary of invitations by the date when they were sent, whether they have been activated, when they have been activated, where they have been activated
 * `Customers` are recognized by their email address

## Term Definitions

 * `application` is a software to which customers might gain access when invited
 * `program` is a single campaign allowing customers to be invited to an application
 * `customer` is a potential user of `application` that can be invited
 * `administrator` is a user of the `system`
 * `system` is the Referral Program Platform itself
