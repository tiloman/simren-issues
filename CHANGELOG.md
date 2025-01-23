# Changelog

## 23.01.2025
- FEATURE: Custom Footer. Admins can now add a custom footer. You can find it under 'Administration - Other'. It's possible to add links, a logo, and a title. Admins can preview the footer before activating it.
- FIX: Bookings where marked as invalid due to insufficient leadtime

## 21.01.2025
- FEATURE: Add Changelog view

## 20.01.2025
- FIX: Notifications were not deletable https://github.com/tiloman/simren-issues/issues/160
- FIX: Translation for 'category' was missing and sort categories in resource filter by name https://github.com/tiloman/simren-issues/issues/158.

## 6.1.2025
- FIX: for invalid bookings it was not posible to make an extension request

## 5.01.2025
- FIX: After handing out booking items, the start date of the booking was updated to the current time. This led to invalid bookings when handing out during closing hours. The start date is now updated to the next available time.
- FEATURE: After adding a resource for a running booking, it is now possible to hand out items even when the booking running. (https://github.com/tiloman/simren-issues/issues/90). Missing items are now displayed in the booking view.

## 4.01.2025
- FIX: Fixed a bug where the dashboard table has reset the start day after toggling the compact view or the names view.
- FIX: Fixed a bug where the main resource was not updated after changing the resources of a booking. (https://github.com/tiloman/simren-issues/issues/61 )
- FEATURE: Added the ability to duplicate bookings (https://github.com/tiloman/simren-issues/issues/146)

## 1.01.2025
- FIX: Fixes a bug where some sections were not toggleable (resource view, booking view, etc.)
- FIX: Fixed a bug where the resource was not available for a booking in edit mode.
- FIX: Display more bookings in the resource calendar view.
- FEATURE: Disabled items are now displayed in the availability charts.
- FEATURE: When a booking is handed out before the start time, the start time is now automatically set to the current time (quarter hours).
- FEATURE: Invalid bookings are now displayed on the dashboard (https://github.com/tiloman/simren-issues/issues/100)
  - invalid bookings are now displayed in a separate section on the dashboard with the corresponding error message.
  - the checkup is triggered automatically after updating bookings, time tables, business hours, offtimes and after disabling, deleting or enabling items
- FEATURE: When a booking is overdue, the corresponding item is now automatically disabled and reenabled after it has been returned. A log entry in the item view is created for this every time.

## 20.12.2024
- FIX: fixed a bug that incorrectly indicated that an item was unavailable when it was actually available. (https://github.com/tiloman/simren-issues/issues/102)

## 14.12.2024
- FIX: Link to resource from booking did not work

## 13.12.2024
- FEATURE: Ability to switch the view between resources and usernames in the dashboard table. (https://github.com/tiloman/simren-issues/issues/151)

## 09.12.2024
- FIX: deprecation warning from various dependencies
- FEATURE: Changelog
- FEATURE: Pagination for Booking view (https://github.com/tiloman/simren-issues/issues/147)

