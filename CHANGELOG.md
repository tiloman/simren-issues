# Changelog

## 4.01.2025
- FIX: Fixed a bug where the dashboard table has reset the start day after toggling the compact view or the names view.
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

