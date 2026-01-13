# SLAPP-106 Instrumentation Ticket: STATUS

This repository contains visual documentation for various app events, user interactions, and performance metrics that are tracked within the application.

## Table of Contents

- [App Lifecycle Events](#app-lifecycle-events)
- [Network Events](#network-events)
- [User Authentication](#user-authentication)
- [User Actions](#user-actions)
- [Performance Metrics](#performance-metrics)
- [PowerSync Events](#powersync-events)
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

## Performance Metrics

These events track application performance including load times and API response times.

### App Load Time
![App Load Time](performance_metric_%20app_load_time.png)

### API Response Time - Success
![API Response Time Success](performance_metric_api_response_time_success.png)

### API Response Time - Failure
![API Response Time Failure](performance_metric_api_response_time_failure.png)

---

## PowerSync Events

These events track PowerSync connection status, synchronization states, and performance metrics.

### PowerSync Connection Time
![PowerSync Connection Time](performance_metric_powersync_connection_time.png)

### PowerSync Connection Status - Connected
![PowerSync Connected](powersync_connection_status_%20connected.png)

### PowerSync Connection Status - Disconnected
![PowerSync Disconnected](powersync_connection_status_%20disconnected.png)

---

## Screen Views

### Screen View
![Screen View](screen_view.png)

---

---

## Summary

This documentation covers the following implemented instrumentation features:

- ✅ **App Lifecycle Events** - Complete tracking of app state transitions
- ✅ **Network Events** - Comprehensive network connectivity monitoring
- ✅ **User Authentication** - Login and logout event tracking
- ✅ **User Actions** - Various user interaction tracking (buttons, scrolls, links, etc.)
- ✅ **Performance Metrics** - App load time and API response time tracking
- ✅ **PowerSync Events** - PowerSync connection status and connection time tracking
- ✅ **Screen Views** - Screen view tracking

All images in this repository are screenshots documenting various events and interactions that can be tracked within the application. These visual references help understand the different types of events that are monitored and logged.
