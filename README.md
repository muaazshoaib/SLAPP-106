# SLAPP-106 Instrumentation Ticket: STATUS

## Remaining items
1. PowerSync, db download, delta files events and bidirectional states
2. Performance metrics (load time, API response time (Right now working APIs: Authentication, Technician clockings, Timecard))
3. OS Permission Events
4. Error and crash tracking Sentry

## DONE: Table of Contents

- [App Lifecycle Events](#app-lifecycle-events)
- [Network Events](#network-events)
- [User Authentication](#user-authentication)
- [User Actions](#user-actions)
- [Screen Views](#screen-views)

---

## App Lifecycle Events

These events track the various states of the application lifecycle.

### App Did Finish Launching
![App Did Finish Launching](app_lifecycle_%20did_finish_launching.png)

### App Did Become Active
![App Did Become Active](app_lifecycle_%20did_become_active.png)

### App Will Resign Active
![App Will Resign Active](app_lifecycle_%20will_resign_active.png)

### App Did Enter Background
![App Did Enter Background](app_lifecycle_%20did_enter_background.png)

### App Will Enter Foreground
![App Will Enter Foreground](app_lifecycle_%20will_enter_foreground.png)

---

## Network Events

These events monitor network connectivity and quality changes.

### Network Changed
![Network Changed](network_changed.png)

### Network Connected - WiFi
![Network Connected WiFi](network_connected_wifi.png)

### Network Connected - Cellular
![Network Connected Cellular](network_connected_cellular.png)

### Network Disconnected
![Network Disconnected](network_disconnected.png)

### Network Quality Updated
![Network Quality Updated](network_quality_updated.png)

---

## User Authentication

These events track user login and logout activities.

### User Logged In
![User Logged In](user_logged_in.png)

### User Logged Out
![User Logged Out](user_logged_out.png)

---

## User Actions

These events capture various user interactions within the application.

### Button Click
![Button Click](user_action_button_click.png)

### Content Scroll
![Content Scroll](user_action_content_scroll.png)

### Link Click
![Link Click](user_action_link_click.png)

### Radio Button
![Radio Button](user_action_radio_button.png)

### Tab Navigation
![Tab Navigation](user_action_tab_navigation.png)

### Toggle Button
![Toggle Button](user_action_toggle_button.png)

---

## Screen Views

### Screen View
![Screen View](screen_view.png)

---

## Notes

All images in this repository are screenshots documenting various events and interactions that can be tracked within the application. These visual references help understand the different types of events that are monitored and logged.
