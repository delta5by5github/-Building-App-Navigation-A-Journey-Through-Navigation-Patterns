# 🚀 Building App Navigation: A Journey Through Navigation Patterns

Welcome to the exploration of Android app navigation! This session dives deep into creating intuitive and user-friendly navigation experiences within your applications. We'll journey through three fundamental navigation patterns: **Bottom Navigation**, the **Navigation Drawer**, and **Tabbed Navigation**.

## 🧭 What You'll Discover

By the end of this session, you'll not only understand the theoretical underpinnings of these navigation patterns but also gain practical skills in implementing them using Jetpack Navigation. You'll learn how to:

* Utilize the **Navigation Drawer** for apps with a larger number of top-level destinations, providing a familiar "hamburger menu" experience.
* Implement **Bottom Navigation** for quick and easy access to a limited set (3-5) of primary, unrelated destinations.
* Design **Tabbed Navigation** for organizing related categories of content that users can easily swipe or tap between.
* Understand the **Android Navigation User Flow**, built around the concept of **destinations** and how they govern movement within your app.
* Differentiate between **primary** and **secondary** destinations and choose the most suitable navigation pattern for your app's specific use case.
* Effectively use the **app bar** in conjunction with these navigation patterns to provide context and facilitate navigation.

## 🗺️ Session Roadmap

Here's a glimpse of the topics we'll be covering:

* **Navigation Overview:** Understanding the core principles of Android app navigation and the role of destinations.
* **Navigation Drawer:** Exploring its structure, implementation, and when it's the ideal choice.
* **Bottom Navigation:** Learning how to implement this popular pattern for seamless access to key sections.
* **Tabbed Navigation:** Discovering how to organize and present related content effectively.

## 🛠️ Hands-on Exercises

This session is packed with practical exercises to solidify your understanding. We'll be building apps incrementally to guide you through each step.

### Exercise 4.01: Creating an App with a Navigation Drawer

In this exercise, you'll build a news or mail app-like interface using a navigation drawer. You'll learn to:

* Set up a new Android project.
* Add necessary Gradle dependencies for Jetpack Navigation.
* Define string resources for your app's content and navigation items.
* Configure your `AndroidManifest.xml` to support the NoActionBar theme.
* Create individual fragments for different sections of your app (Home, Favorites, Recents, Archive, Bin, Settings, Content).
* Design simple layouts for each fragment to display corresponding content.
* Create a **Navigation Graph** (`mobile_navigation.xml`) to define the destinations and navigation actions within your app.
* Implement click listeners in your fragments to navigate between destinations using the Navigation component.
* Create a **Nav Host Fragment** (`content_main.xml`) to host your app's content.
* Design a **Navigation Drawer Header** (`nav_header_main.xml`) for branding and user information.
* Create an **App Bar Layout** (`app_bar_main.xml`) with a Toolbar.
* Add **Vector Assets** for menu item icons.
* Define a **Menu Resource** (`activity_main_drawer.xml`) for the items in your navigation drawer, linking them to your navigation graph destinations.
* Update your main activity layout (`activity_main.xml`) to include the `DrawerLayout`, `AppBarLayout`, `NavigationView`, and `NavHostFragment`.
* Implement the logic in your `MainActivity.kt` to:
    * Set up the Toolbar as the ActionBar.
    * Retrieve the `NavController` from the `NavHostFragment`.
    * Configure the `AppBarConfiguration` to manage the display of the Up button and the Navigation Drawer icon for top-level destinations.
    * Connect the `NavigationView` with the `NavController` to handle item clicks.
    * Override `onSupportNavigateUp()` to handle Up button presses.
* Add an **Overflow Menu** (`main.xml`) to the app bar for secondary navigation options like Settings.
* Implement `onCreateOptionsMenu()` and `onOptionsItemSelected()` in `MainActivity.kt` to inflate and handle clicks on the overflow menu items.

### Exercise 4.02: Adding Bottom Navigation to Your App

In this exercise, you'll transition to using bottom navigation for a loyalty app with a limited number of primary destinations (Home, Tickets, Offers, Rewards). You'll learn to:

* Create a new Android project.
* Add the necessary Gradle dependencies.
* Define string resources for your bottom navigation items and fragment content.
* Create corresponding fragments for each bottom navigation item (Home, Content, Offers, Rewards, Settings, Tickets, Cart).
* Reuse or create appropriate layouts for these fragments.
* Define a **Navigation Graph** (`mobile_navigation.xml`) for the bottom navigation destinations.
* Update the `onCreateView` in your `HomeFragment` (or another relevant fragment) to include navigation actions.

**(Further exercises on Tabbed Navigation will likely follow in the complete session.)**

## 🔗 Useful Links

* **Complete Navigation Drawer Code:** [https://packt.link/ZRDiT](https://packt.link/ZRDiT)
* **Vector Assets:** [https://packt.link/CurtF](https://packt.link/CurtF)
* **Full List of `app:showAsAction` Values:** [https://developer.android.com/guide/topics/resources/menu-resource](https://developer.android.com/guide/topics/resources/menu-resource)
* **Complete Bottom Navigation Code:** [https://packt.link/Fwuyl](https://packt.link/Fwuyl)

## Let's Navigate! 🚀

Get ready to embark on a journey to master Android app navigation. By the end of this session, you'll be equipped with the knowledge and skills to create seamless and intuitive navigation experiences for your users!
