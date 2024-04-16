## Good points
- It uses repository pattern 
- It uses helpers (need to maximize the usage) 

## Suggestion for improvement
- make readable conditions, as much as possible reduce nesting and make it more simplified.
- followed consistent naming conventions for variable (ex `$job_ids` should be `$jobs` since it return object not ids )
- avoid too long code in one line , especially in returning too many variables.
- don't hesistate to use private functions for the sake of readability. 
- try to use switch case since it is more faster than if else condition.
- For me, remove the commented code if necessary, since it has git so we can preview the history and to make it more cleaner.
- try to language localization for dynamic language location. (ex `__('label_text')`)

## To Do

- Add flash message (I add `session()->flash()`) :white_check_mark:
- remove method and add service for notification TEMP method send session start remind notification (I add new file called `NotificationService` under `Service` folder) :white_check_mark:

Sidenote: *I only finished two task*

## Summary
All in all, still need to improve the code and make it more readable. Consider adding comments to clarify complex or critical sections of the code, especially if it involves business logic or custom methods.

*Refactor by: Jerome Suyat*