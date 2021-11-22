---
title: How to Set Up Event Notifications
description: Learn how to control which email and in-app notifications [!DNL Adobe Workfront] users receive by managing event notifications.
---

<!---
this has the same content as the system administrator notification setup and mangement section of the email and inapp notificiations learning path
--->

<!---
add URL link in the note at the top of the LP
--->

# Set up event notifications

>[!NOTE]
>
>Because of a phased rollout, the functionality that allows system and group administrators to manage event notifications is temporarily not available for some [!DNL Workfront] customers. Please follow this [!DNL Workfront One] article for updates regarding the release: Unlock configuration of event notifications for groups.

System administrators determine which notifications users should receive through [!DNL Workfront].

![[!UICONTROL Email Notifications] window in the [!UICONTROL Setup] area](assets/admin-fund-notifications-1.png)

The [!UICONTROL Event Notifications] list is grouped by type. For each event notification listed, you’ll see five pieces of information:

* **[!UICONTROL Active] —** The [!UICONTROL Active] column allows you to turn a notification on or off at a system-wide level.
* **[!UICONTROL Name] —** This is the name of the notification within [!DNL Workfront].
* **[!UICONTROL Description] —** The description provides a brief explanation of what action took place to trigger a notification or needs to be taken in response to receiving the notification.
* **[!UICONTROL Email Subject] —** What will be displayed to the user in the subject line when the email is sent to users.
* **[!UICONTROL Group Access] —** Unlock notifications so they can be managed by group administrators. 

## Turn on notifications

To manage notifications at a global system level, make sure the search bar says [!UICONTROL System Event Notifications]. 

Turn on a specific notification to make it available for all users by clicking the toggle button so the blue is showing. If the blue is hidden, the notification is off.

![[!UICONTROL Active] column on [!UICONTROL Email Notifications] page](assets/admin-fund-notifications-2.png)

Once an event notification is turned on, messages are sent instantly when the event occurs.

## Allow group administrator control

Group administrators can be given permission, by system administrators, to customize the notification list further based on how their groups and subgroups function and what their workflows are.

To give group admins the ability to manage notifications for their groups and subgroups, the system-level notifications need to be unlocked. To do this, make sure the search bar says [!UICONTROL System Event Notifications]. Find the notification and click the toggle button so it’s blue. This will unlock the notification option and allow top-level group administrators to determine if that notification is needed for their groups and subgroups. Subgroups inherit the notification configurations from their top parent group.

![[!UICONTROL Group Access] column on [!UICONTROL Email Notifications] page](assets/admin-fund-notifications-5.png)

### Manage group notifications

Once the system administrator has unlocked notification options, the group administrators can manage a group’s notifications from the individual [!UICONTROL Group] page, by clicking [!UICONTROL Event Notifications] in the left panel menu. Then you can activate or deactivate notification options.

![Group page with Event Notifications section selected](assets/admin-fund-notifications-4.png)

If needed, system administrators can manage a group’s notifications from the [!UICONTROL Notifications] page by entering the group name in the search bar at the top of the window.

![Event Notifications page](assets/admin-fund-notifications-3.png)

## Pro tips

There are some notifications [!DNL Workfront] recommends making available to your users.

For most users:

* [!UICONTROL A predecessor of one of my tasks is completed]
* [!UICONTROL Someone includes me on a directed update]
* [!UICONTROL Someone comments on my work item]
* [!UICONTROL The due date changes on a task I’m assigned to]
 

Specifically for project managers:

* [!UICONTROL A project I’m on becomes active]
* [!UICONTROL A project I own gets behind]
* [!UICONTROL An issue is added to a project I own]
* [!UICONTROL Milestone task is completed on a project I own]

<!---
guides: manage your notifications and notifications for admins
--->
