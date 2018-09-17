# Attendance_system

## 1. How to use
1. Fork and edit, push, merge as usual

2. I install Google Chrome extension

Chrome extension:

https://chrome.google.com/webstore/detail/google-apps-script-github/lfjcgcmkmjjlieihflfhjopckgpelofo

Explanation of extension:

https://github.com/leonhartX/gas-github

3. Go to below Page

https://script.google.com/a/kemuri.in/d/1-keOTtQZPxqjkPqzVKb6T6rHKREsfN0-BZnap17kTGnRET4vCOu3Vc2Z/edit?usp=sharing

4. Change the place of `Repo` in upside to `KemuriTechnology/Attendance_system`

5. Tap the button of `Pull` in upside ( **Don’t tap `Push`** )

6. Go to `File` → `Manage versions…` → `Save new version`

7. Go to `Publish` → `Deploy as Web app…`

8. Set project version to newest one.

Reference:

Spread sheet is below. After you talk with ohnishi-san, your tab will appear.

https://docs.google.com/spreadsheets/d/1N7SvkA36yC0EbjM5d9YGpIQz6q5GAAzMp1AE5-NvIeU/edit?usp=sharing

## 2. Commands

### About working time

- Start working : `Hello`, `Hi!`, `Good morning`

- Delete starting time : `Hello cancel`

- Modify starting time : `Hello hh:mm` [ eg. Hello 12:30 (When you modify starting time to 12:30) ]

- Finish working : `See you`, `Bye`

- Delete ending time : `Bye cancel`

- Modify ending time : `Bye hh:mm` [ eg. Bye 12:30 (When you modify ending time to 12:30) ]

### About lunch time

- Register lunch time : `lunch time hh:mm` [ eg. lunch time 00:15 (The case your lunch time is 15 minutes) ]

- Start lunch (Additional) : `start lunch`

- Delete lunch start time : `start lunch cancel`

- Modify lunch start time : `start lunch hh:mm`

- Finish lunch (Additional) : `finish lunch`

- Delete lunch end time : `finish lunch cancel`

- Modify lunch end time : `finish lunch hh:mm`

### About holiday and leave

- Register holiday : `holiday MM/DD`, `holiday today`, `holiday tomorrow`, `holiday yesterday` [ eg. holiday 09/05 (The case you register holiday in September 5) ]

- Delete holiday : `holiday MM/DD cancel`, `holiday today cancel`, `holiday tomorrow cancel`, `holiday yesterday cancel` 

- Register leave : `leave MM/DD`, `leave today`, `leave tomorrow`, `leave yesterday` [ eg. leave 09/05 (The case you register leave in September 5) ]

- Delete leave : `leave MM/DD cancel`, `leave today cancel`, `leave tomorrow cancel`, `leave yesterday cancel` 

### About Rremote work

- Register remote work : `remote MM/DD`, `remote today`, `remote tomorrow`, `remote yesterday` [ eg. remote 09/05 (The case you register remote work in September 5) ]

- Delete remote work : `remote MM/DD cancel`, `remote today cancel`, `remote tomorrow cancel`, `remote yesterday cancel` 
