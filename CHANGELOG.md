#5.1.1
---

* Update version matrix information

---

## [5.3.0] - 2023-05-02
- bda99c8: Add support for Laravel v11, and drop support for Laravel v9
- 627880b: Update phpunit to v10.1 from v9.5
- 232f115: Drop PHP v8.0 support and update composer dependencies

#5.1.0
---

* Improved configuration options
* Create new containers dynamically
* Add messages via closures
* Removed message aliasing
* Improved message positioning
* Render messages via blade extension

---

#5.0.0
---

* Fully supported Laravel 5

---

#4.0.0
---

* Support for Laravel 5

---

# 2.0.1
---

* Fix ```$this``` usage when in Closure in ServiceProvider

---

# 2.0.0
---

* Add message types dynamically
* Changes in position and alias API
* Added events
* Updated ```config.php``` file
* Messages now flashed using events
* Refactored library

---

# 1.2.3
---

* Check if ```session.store``` is set before using it.

---

# 1.2

---

* Refactored how messages are stored in bag.
* Added method ```getAtPosition($position)``` to a NotificationBag.
* Added method ```getAliased($alias)``` to a NotificationBag and Collection classes.
* Added method ```group()``` to NotificationBag to allow render grouping.
* When working directly with ```Notification```, you will work just with default container.
* Session prefix now is configurable.
* Refactored ```Notification``` class, now uses ```__call()``` to call methods on a default container.

---

# 1.1.1

---

* Added test to test message flashing after adding alias and / or position.
* Fix message flashing when using ```alias()``` and / or ```atPosition```.

---

# 1.1

---

* Added methods to clear notifications for a given type / all in a container.
* Message aliasing, allows to use alias on message, so it can be overridden when needed.
* Message positioning.

---

# 1.0.1

---

* Fixed $app scopes when registering component.

---

# 1.0

---

* Initial release.
