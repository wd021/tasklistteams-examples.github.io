![TaskList logo](https://s3.amazonaws.com/tasklistguru/tasklist.png)

<h5>
TaskList is a task manager for your Microsoft Teams team. Here's a guide on how to use it.
</h5>

?> Remember, you must add the TaskList bot to a team in your **teams** section. Every team member has access to the same commands.

## Add Tasks

Use **`task`** to add a task. Add tags to categorize them (**`@users`** and/or **`#tags`**).

```examples
@tasklist task Discuss new design plans! @Allison @Dan #design
@tasklist task Prepare for tokyo event @everyone #meetings
@tasklist task Walkthrough product v2 @me @Jessica
```

?>&bull; You can use **@me**, **@everyone**, or **@username** for **`@users`**.<br />&bull; If you create a task with no tags, it will automatically be assigned to **@everyone**

## View Tasks

Use **`list`** to view a list of all your tags.

```examples
@tasklist list
```

Use **`list [@user/#tag]`** to view tasks for a specific tag.

```examples
@tasklist list @everyone
@tasklist list @Allison
@tasklist list #design
```
