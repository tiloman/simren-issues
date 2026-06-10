# Changelog

## v1.2.94 - 2026-06-10
- **FEATURE**: The user list now shows names as "last name, first name" with the email address in its own column, making it easier to find people (https://github.com/tiloman/simren-issues/issues/176)

## v1.2.93 - 2026-06-10
- **FEATURE**: Teams can now customize the texts of booking emails (subject and content, German and English) with their own wording and placeholders like name or booking date.

## v1.2.92 - 2026-06-10
- **FEATURE**: The booking log now records every automated email, including who received it (https://github.com/tiloman/simren-issues/issues/288)

## v1.2.91 - 2026-06-10
- **FIX**: Sorting and status filtering on the bookings list now work together instead of resetting each other (https://github.com/tiloman/simren-issues/issues/257)
- **FEATURE**: The bookings list can now be filtered by a concrete date range (von/bis) (https://github.com/tiloman/simren-issues/issues/257)

## v1.2.90 - 2026-06-10
- **FIX**: Booking update emails are no longer sent to the wrong user when changing the cart owner
- **FIX**: Selecting a user in the cart no longer triggers a premature "Booking updated" email

## v1.2.89 - 2026-06-10
- **FEATURE**: Teams can now choose between informal (du) and formal (Sie) address forms in settings

## v1.2.88 - 2026-06-10
- **FIX**: Availability check now happens when adding items to cart, not just when submitting the booking

## v1.2.87 - 2026-06-10
- **FIX**: Users with recent bookings are no longer marked as inactive, even if they haven't logged in themselves

## v1.2.86 - 2026-06-10
- **FIX**: Edit requests could silently disappear, leaving bookings stuck in extension request state

## v1.2.85 - 2026-06-10
- **FIX**: Changing cart owner no longer resets the description field
- **FIX**: "Booking created" popup no longer appears when changing cart owner
- **FIX**: Items added to a booking after check-in are now correctly marked as unavailable
- **FIX**: Admins can now delete cart bookings assigned to other users
- **FIX**: Copying a booking now carries over the original booking's user

## v1.2.84 - 2026-06-10
- **FIX**: Off times index crashes when `selection` is nil

## v1.2.83 - 2026-06-10
- **FIX**: Bookings with many resources caused duplicate item assignments during check-in (https://github.com/tiloman/simren-issues/issues/272)

## v1.2.82 - 2026-06-10
- **FIX**: Several minor issues
- **FEATURE**: Add custom colors to sites (https://github.com/tiloman/simren-issues/issues/261)

## v1.2.81 - 2026-06-10
- **IMPROVEMENT**: Redirect to booking after creating a direct booking
- **IMPROVEMENT**: Inline user select for changing the booking user
- **FIX**: Cart success modal was not displayed after changing the booking user
- **FIX**: Items removed during check-out were not released and remained unavailable

## v1.2.8 - 2026-06-10
**FEATURE**: Added Basket feature. From now on bookings will be created via basket.

## v1.2.72 - 2026-06-10
- **FIX**: Find invalid bookings job no longer crashes when user has been deleted
- **FIX**: Navbar policy no longer crashes when user is nil
- **FIX**: Booking details mail template no longer crashes when user has been deleted

## v1.2.71 - 2026-06-10
- **FIX**: Item detail page no longer crashes when linked bookings have been deleted

## v1.2.7 - 2026-06-10
- **FEATURE**: Save Bookings as draft
- **FEATURE**: Resolve bookings with state 'Problem' (https://github.com/tiloman/simren-issues/issues/222)
- **FIX**: Availability check for packages did not take into account a specific site

## v1.2.61 - 2026-06-10
- **FIX**: Fix datefilter for xml export

## v1.2.6 - 2026-06-10
- **FEATURE**: improved statistic graphs (new datefilter, bookings by article) (https://github.com/tiloman/simren-issues/issues/271)
- **FEATURE**: Add xml download for some statistics

## v1.2.51 - 2026-06-10
- **MAINTENANCE**: Security updates

## v1.2.5 - 2026-06-10
- **FEATURE**: refactor Site specific settings

## v1.2.4 - 2026-06-10
- **MISC**

## v1.2.3 - 2026-06-10
- **FEATURE**: Add site specific timegap and leadtime (Beta - hidden)

## v1.2.2 - 2026-06-10
- **FIX**: cancelled bookings were shown by mistake in dashboard overview (https://github.com/tiloman/simren-issues/issues/269 & https://github.com/tiloman/simren-issues/issues/224)

## v1.2.1 - 2026-06-10
- **FEATURE**: Ability to set default theme per team
- **FEATURE**: Add 'corporate' theme

## v1.2.0 - 2026-06-10
- **FEATURE**: Design improvements and seperated administration area. Set theme in personal settings

## v1.1.60 - 2026-06-10
- **FIX**: Bookings were not displayed in the dashboard table (https://github.com/tiloman/simren-issues/issues/256 & https://github.com/tiloman/simren-issues/issues/240)

## v1.1.59 - 2026-06-10
- **FIX**: Added missing libraries for image processing

## v1.1.58 - 2026-06-10
- **FIX**: fixes for direct booking
- **FEATURE**: Show more data in global overview

## v1.1.57 - 2026-06-10
- **MAINTENANCE**: Upgrade underlying platform

## v1.1.56 - 2026-06-10
- **MAINTENANCE**: Improve SVG Icon handling

## v1.1.55 - 2026-06-10
- **FEATURE**: Added display of handed out resources (items) count to statistics overview
- **IMPROVEMENT**: Reorganized statistics overview with sections "Gesamt" and "Letzte 30 Tage" for better clarity

## v1.1.54 - 2026-06-10
- **FIX**: Fixed duplicate sites appearing in statistics page site filter (https://github.com/tiloman/simren-issues/issues/252)
- **FIX**: Fixed statistics showing cancelled and destroyed bookings in all counts and charts (https://github.com/tiloman/simren-issues/issues/253)

## v1.1.53 - 2026-06-10
- **FEATURE**: added more filter to statistics page
- **IMPROVEMENT**: Remove booking filter from users view and add pagination to user view (https://github.com/tiloman/simren-issues/issues/249)
- **FEATURE**: Internal user comments are now displayed in direct booking form when a user is selected (https://github.com/tiloman/simren-issues/issues/251)
- **FEATURE**: Added sorting functionality for Type, Status, and Bookings columns in items index (https://github.com/tiloman/simren-issues/issues/225)
- **FIX**: Fixed an issue where bookings were not displayed in the dashboard day overview (https://github.com/tiloman/simren-issues/issues/240)

## v1.1.52 - 2026-06-10
- **MAINTENANCE**: Improve Icon handling

## v1.1.51 - 2026-06-10
- **FEATURE**: Add ability to change the booking while handing out items (https://github.com/tiloman/simren-issues/issues/54)

## v1.1.5 - 2025-09-11
- **FIX**: When editing a booking, the end date selection was set to the next business day after the selected start date (https://github.com/tiloman/simren-issues/issues/247)

## v1.1.45 - 2025-09-05
- **FEATURE**: Add Date to changelog
- **Maintenance**: Depedency updates and security improvements

## v1.1.44 - 2025-07-24
- **FIX**: Fixes an issue where a booking was faulty in edit request state (https://github.com/tiloman/simren-issues/issues/233)

## v1.1.43 - 2025-07-23
- **FIX**: Fix timestamp style for comments (https://github.com/tiloman/simren-issues/issues/244)

## v1.1.42 - 2025-07-21
- **FIX**: Fixed an issue for direct bookings in combination with required descriptions(https://github.com/tiloman/simren-issues/issues/237)
- **FIX**: Fixes an issue where start time could not be edited for upcoming bookings (https://github.com/tiloman/simren-issues/issues/243)

## v1.1.41 - 2025-07-17
- **FIX**: Fixed an issue where validation messages are not deleted properly (https://github.com/tiloman/simren-issues/issues/235)
- **FIX**: Sort resources alphabetically in direct booking view (https://github.com/tiloman/simren-issues/issues/238)

## v1.1.40 - 2025-07-01
- **FIX**: Fixed an issue where packages could be booked despite unavailable resources

## v1.1.39 - 2025-06-24
- **FEATURE**: Some style adjustments
- **FIX**: Sort by name in item view (https://github.com/tiloman/simren-issues/issues/225)

## v1.1.38 - 2025-06-17
- **FEATURE**: Show offtimes in dashboard table (https://github.com/tiloman/simren-issues/issues/223)
- **FIX**: Set end date to end of day for offtimes (https://github.com/tiloman/simren-issues/issues/205)

## v1.1.37 - 2025-06-16
- **FEATURE**: Added option to make booking description mandatory (https://github.com/tiloman/simren-issues/issues/228)

## v1.1.36 - 2025-06-02
- **Maintenance**: Depedency updates and security improvements

## v1.1.35 - 2025-05-27
- **FIX**: Validate that the new end date for an edit request differs from current end date. Also skip max duration validation for edit requests

## v1.1.34 - 2025-05-24
- **FIX**: Swagger file for api documentation was faulty

## v1.1.33 - 2025-05-20
- **FIX**: fixed an error where the timegap before booking was not being handled correctly for bookings with multiple articles per resource
- **FEATURE**: improved error handling
- **FIX**: maximum of simultaneous bookings for a device could not be set in form
- **FEATURE**: Show validation errors in booking view for invalid bookings

## v1.1.32 - 2025-05-09
- **FIX**: Fixed partially returned items being incorrectly disabled when booking becomes overdue (https://github.com/tiloman/simren-issues/issues/230)
- **MAINTENANCE**: Dependency updates

## v1.1.31 - 2025-04-23
- **FIX**: Fixed page reload issue after booking confirmation

## v1.1.3 - 2025-04-14
- **FEATURE**: Added Booking Log (https://github.com/tiloman/simren-issues/issues/216)
- **FIX**: Fixed incorrect checkout process for room resources

## v.1.1.26 - 2025-04-23
- **FEATURE**: Added more users and resources to statistics graph
- **FIX**: Fixed datepicker end date mismatch when editing bookings (https://github.com/tiloman/simren-issues/issues/210)
- **FEATURE**: Added 48-hour overdue booking reminder (https://github.com/tiloman/simren-issues/issues/217)
- **FIX**: Fixed inconsistency in calendar views for running bookings between resource and all-bookings view

## v1.1.25 - 2025-04-08
- **FIX**: Fixed day change issue when switching dashboard table view with today selected (https://github.com/tiloman/simren-issues/issues/211)
- **FIX**: Alphabetically sorted resources in statistics view (https://github.com/tiloman/simren-issues/issues/214)

## v1.1.24 - 2025-04-07
- **FEATURE**: Added resource count display in dashboard table (https://github.com/tiloman/simren-issues/issues/180)

## v1.1.23 - 2025-04-07
- **FIX**: Fixed "Show all resources" button resetting booking form values (https://github.com/tiloman/simren-issues/issues/112 & https://github.com/tiloman/simren-issues/issues/168)
- **FEATURE**: Support for WEBP images
- **FIX**: After deleting a booking the user was not redirected to bookings path (https://github.com/tiloman/simren-issues/issues/203)

## v1.1.22 - 2025-04-03
- **FIX**: Show error message when deleting a resource fails (https://github.com/tiloman/simren-issues/issues/209)

## v1.1.21 - 2025-04-01
- **FIX**: Improve error handling for edit requests
- **FEATURE**: Show offtimes in resource calendar view (https://github.com/tiloman/simren-issues/issues/206)

## v1.1.20 - 2025-04-01
- **FEATURE**: File input field validates file format on client side
- **MAINTENANCE**: Automatic User deletion improvements

## v.1.1.19 - 2025-03-24
- **FIX**: New bookings with end date inside the timegap of the following booking could be created.
- **FIX**: Booking user was informed about new comments even for internal comments

## v.1.1.18 - 2025-03-17
- **MAINTENANCE**: Remove legacy comment model

## v.1.1.17 - 2025-03-16
- **FIX**: Tooltips were not displayed correctly (https://github.com/tiloman/simren-issues/issues/199)
- **FIX**: Add missing translation (https://github.com/tiloman/simren-issues/issues/194)
- **FIX**: fix redirect path after updating notifications
- **FIX**: New comment mail was not sent to the booking user. Added the option to opt-out new comment mails for users (https://github.com/tiloman/simren-issues/issues/198)
- **FIX**: Timetables only for rooms (https://github.com/tiloman/simren-issues/issues/197)
- **FEATURE**: Add type badge to resources (https://github.com/tiloman/simren-issues/issues/195)
- **FIX**: Consider configured mail server for sending invalid bookings mail (https://github.com/tiloman/simren-issues/issues/191)
- **FIX** : Sort resources by alphabet in timetable form (https://github.com/tiloman/simren-issues/issues/196)
- **FIX**: Improved response mode for login page (https://github.com/tiloman/simren-issues/issues/183)
- **FEATURE**: The booking details are now shown per default (https://github.com/tiloman/simren-issues/issues/179)

## v1.1.16 - 2025-02-26
- **FIX**: In some cases it was possible that multiple mails were sent after setting an item to inactive (https://github.com/tiloman/simren-issues/issues/173)


## v1.1.15 - 2025-02-25
- **FIX**: Fixed an issue where a user could not be destroyed due to associations with the new comment model
- **FIX**: Ensure the right subdomain in invitation mail and some other small issues for the invitation process

## v1.1.14 - 2025-02-23
- **FEATURE**: Complete refactoring of the comment model including the option to create internal comments (https://github.com/tiloman/simren-issues/issues/133).
- **FIX**: Sort accessories alphabetically in resources form

## v1.1.13 - 2025-02-20
- **FEATURE**: increase image resolution for ressources (max width from 1000px to 1400px)

## v1.1.12 - 2025-02-16
- **FIX**: If no user was selected in combination with anonymous bookings, the booking could not be submitted (https://github.com/tiloman/simren-issues/issues/167).
- **FIX**: Mailpreference form was not submittable
- **FEATURE**: Preselect enddate after selecting a startdate (https://github.com/tiloman/simren-issues/issues/145)
- **FEATURE**: Opt out for new group notification mail (https://github.com/tiloman/simren-issues/issues/157). Defaults to false

## v1.1.11 - 2025-02-08
- **FIX**: reset filter link for resources view (https://github.com/tiloman/simren-issues/issues/166)
- **FIX**: Team infos were displayed wrong after failed login (https://github.com/tiloman/simren-issues/issues/162)

## v1.1.10 - 2025-02-05
- **FIX**: Sort resources by name (https://github.com/tiloman/simren-issues/issues/165)
- **MAINTENANCE**: Code refactoring and preparations for upcoming update (Rails 6 -> Rails 7)
- **FEATURE**: Changed wording for welcome page (https://github.com/tiloman/simren-issues/issues/164)

## v1.1.9 - 2025-02-02
- **FIX**: Reset to_be_deleted status after successful login
- **FEATURE**: Add extra Filter for users who will be destroyed. Add info in edit user view.
- **FEATURE**: Finally perform user deletion after inactivity for a specific time (last login). This time can be set in team settings. Defaults to 5 years. https://github.com/tiloman/simren-issues/issues/120

## v1.1.8 - 2025-01-23
- **FEATURE**: Custom Footer. Admins can now add a custom footer. You can find it under 'Administration - Other'. It's possible to add links, a logo, and a title. Admins can preview the footer before activating it.
- **FIX**: Bookings where marked as invalid due to insufficient leadtime
- **FIX**: When overdue bookings were extended, previously deactivated items were not reactivated

## v1.1.7 - 2025-01-23
- **FEATURE**: Add Changelog view

## v1.1.6 - 2025-01-23
- **FIX**: Notifications were not deletable
- **FIX**: Translation for 'category' was missing and sort categories in resource filter by name

## v1.1.5 - 2025-01-23
- **FIX**: for invalid bookings it was not posible to make an extension request

## v1.1.4 - 2025-01-23
- **FIX**: After handing out booking items, the start date of the booking was updated to the current time. This led to invalid bookings when handing out during closing hours. The start date is now updated to the next available time.

## v1.1.3 - 2025-01-23
- **FIX**: Fixed a bug where the dashboard table has reset the start day after toggling the compact view or the names view.
- **FIX**: Fixed a bug where the main resource was not updated after changing the resources of a booking.
- **FEATURE**: Added the ability to duplicate bookings

## v1.1.2 - 2025-01-23
- **FIX**: Fixes a bug where some sections were not toggleable (resource view, booking view, etc.)
- **FIX**: Fixed a bug where the resource was not available for a booking in edit mode.
- **FIX**: Display more bookings in the resource calendar view.
- **FEATURE**: Disabled items are now displayed in the availability charts.
- **FEATURE**: When a booking is handed out before the start time, the start time is now automatically set to the current time (quarter hours).
- **FEATURE**: Invalid bookings are now displayed on the dashboard
  - invalid bookings are now displayed in a separate section on the dashboard with the corresponding error message.
  - the checkup is triggered automatically after updating bookings, time tables, business hours, offtimes and after disabling, deleting or enabling items
- **FEATURE**: When a booking is overdue, the corresponding item is now automatically disabled and reenabled after it has been returned. A log entry in the item view is created for this every time.

## v1.1.1 - 2025-01-23
- **FIX**: fixed a bug that incorrectly indicated that an item was unavailable when it was actually available.

## v1.1.0 - 2025-01-23
- **FIX**: Link to resource from booking did not work

## v1.0.9 - 2025-01-23
- **FEATURE**: Ability to switch the view between resources and usernames in the dashboard table.

## v1.0.8 - 2025-01-23
- **FIX**: deprecation warning from various dependencies
- **FEATURE**: Changelog
- **FEATURE**: Pagination for Booking view

