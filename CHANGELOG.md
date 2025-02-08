# Changelog

## v1.1.11
- **FIX**: reset filter link for resources view (https://github.com/tiloman/simren-issues/issues/166)
- **FIX**: Team infos were displayed wrong after failed login (https://github.com/tiloman/simren-issues/issues/162)

## v1.1.10
- **FIX**: Sort resources by name (https://github.com/tiloman/simren-issues/issues/165)
- **MAINTENANCE**: Code refactoring and preparations for upcoming update (Rails 6 -> Rails 7)
- **FEATURE**: Changed wording for welcome page (https://github.com/tiloman/simren-issues/issues/164)

## v1.1.9
- **FIX**: Reset to_be_deleted status after successful login
- **FEATURE**: Add extra Filter for users who will be destroyed. Add info in edit user view.
- **FEATURE**: Finally perform user deletion after inactivity for a specific time (last login). This time can be set in team settings. Defaults to 5 years. https://github.com/tiloman/simren-issues/issues/120

## v1.1.8
- **FEATURE**: Custom Footer. Admins can now add a custom footer. You can find it under 'Administration - Other'. It's possible to add links, a logo, and a title. Admins can preview the footer before activating it.
- **FIX**: Bookings where marked as invalid due to insufficient leadtime
- **FIX**: When overdue bookings were extended, previously deactivated items were not reactivated

## v1.1.7
- **FEATURE**: Add Changelog view

## v1.1.6
- **FIX**: Notifications were not deletable
- **FIX**: Translation for 'category' was missing and sort categories in resource filter by name

## v1.1.5
- **FIX**: for invalid bookings it was not posible to make an extension request

## v1.1.4
- **FIX**: After handing out booking items, the start date of the booking was updated to the current time. This led to invalid bookings when handing out during closing hours. The start date is now updated to the next available time.

## v1.1.3
- **FIX**: Fixed a bug where the dashboard table has reset the start day after toggling the compact view or the names view.
- **FIX**: Fixed a bug where the main resource was not updated after changing the resources of a booking.
- **FEATURE**: Added the ability to duplicate bookings

## v1.1.2
- **FIX**: Fixes a bug where some sections were not toggleable (resource view, booking view, etc.)
- **FIX**: Fixed a bug where the resource was not available for a booking in edit mode.
- **FIX**: Display more bookings in the resource calendar view.
- **FEATURE**: Disabled items are now displayed in the availability charts.
- **FEATURE**: When a booking is handed out before the start time, the start time is now automatically set to the current time (quarter hours).
- **FEATURE**: Invalid bookings are now displayed on the dashboard
  - invalid bookings are now displayed in a separate section on the dashboard with the corresponding error message.
  - the checkup is triggered automatically after updating bookings, time tables, business hours, offtimes and after disabling, deleting or enabling items
- **FEATURE**: When a booking is overdue, the corresponding item is now automatically disabled and reenabled after it has been returned. A log entry in the item view is created for this every time.

## v1.1.1
- **FIX**: fixed a bug that incorrectly indicated that an item was unavailable when it was actually available.

## v1.1.0
- **FIX**: Link to resource from booking did not work

## v1.0.9
- **FEATURE**: Ability to switch the view between resources and usernames in the dashboard table.

## v1.0.8
- **FIX**: deprecation warning from various dependencies
- **FEATURE**: Changelog
- **FEATURE**: Pagination for Booking view

