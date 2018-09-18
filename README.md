# Attendance_system

## 1. Commands

### Working time

- Start working : `Hello`, `Hi!`, `Good morning`

- Delete starting time : `Hello cancel`

- Modify starting time : `Hello hh:mm` [ eg. Hello 12:30 (When you modify starting time to 12:30) ]

- Finish working : `See you`, `Bye`

- Delete ending time : `Bye cancel`

- Modify ending time : `Bye hh:mm` [ eg. Bye 12:30 (When you modify ending time to 12:30) ]

### Lunch time

- Register lunch time : `lunch time hh:mm` [ eg. lunch time 00:15 (The case your lunch time is 15 minutes) ]

- Start lunch (Additional) : `start lunch`

- Delete lunch start time : `start lunch cancel`

- Modify lunch start time : `start lunch hh:mm`

- Finish lunch (Additional) : `finish lunch`

- Delete lunch end time : `finish lunch cancel`

- Modify lunch end time : `finish lunch hh:mm`

### Holiday and leave

- Register holiday : `holiday MM/DD`, `holiday today`, `holiday tomorrow`, `holiday yesterday` [ eg. holiday 09/05 (The case you register holiday in September 5) ]

- Delete holiday : `holiday MM/DD cancel`, `holiday today cancel`, `holiday tomorrow cancel`, `holiday yesterday cancel` 

- Register leave : `leave MM/DD`, `leave today`, `leave tomorrow`, `leave yesterday` [ eg. leave 09/05 (The case you register leave in September 5) ]

- Delete leave : `leave MM/DD cancel`, `leave today cancel`, `leave tomorrow cancel`, `leave yesterday cancel` 

### Remote work

- Register remote work : `remote MM/DD`, `remote today`, `remote tomorrow`, `remote yesterday` [ eg. remote 09/05 (The case you register remote work in September 5) ]

- Delete remote work : `remote MM/DD cancel`, `remote today cancel`, `remote tomorrow cancel`, `remote yesterday cancel` 

### Check status

- Check worker : `who is working?`
- Check holiday people : `who is holiday?`


## 2. How to edit source code
1. Fork and edit, push, merge as usual

2. Install below google chrome extension

https://chrome.google.com/webstore/detail/google-apps-script-github/lfjcgcmkmjjlieihflfhjopckgpelofo

(Reference) Explanation of the extension:
https://github.com/leonhartX/gas-github

3. Go to GAS editor page.

4. Change the place of `Repository` in upside to `KemuriTechnology/Attendance_system`

5. Tap the button of `Pull` in upside ( **Don’t tap `Push`** )

6. Go to `File` → `Manage versions…` → `Save new version`

7. Go to `Publish` → `Deploy as Web app…`

8. Set project version to newest one.

9. Talk and check spread sheet.



