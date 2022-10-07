September update  
Things are coming together!
[Read more...](https://blog.zinzen.me/2022/10/07/App-update.html)   

@Testers: 🙏**THANK YOU**🙏 !  
@All users: Please use [the feedback page](https://zinzen.me/Home/ZinZen/Feedback).

## Visible updates 🎁🎁🎁
- **Edit in place**  
[Tushar](https://github.com/Tushar-4781) implemented a way to edit a goal without leaving the screen.  
Previously you would be taken to a separate screen from which you then had to navigate back or press a save button:  
<img src="/img/edit_in_place.gif" alt="edit-in-place" width="400"/>  

- **Add goals from archive**  
In addition to the add from public goals (goals shared anonymously amongst the community) [Tushar](https://github.com/Tushar-4781) now also implemented a way to add back goals you've previously completed.  
Very handy for a shopping 🛒 or a holiday packing list!✈️🌴⛱️   
<img src="/img/add_goals_from_archive.gif" alt="add-goals-from-archive" width="400"/>  

- **First screens for sharing privately**  
[Mallika](https://github.com/mallikarai05) did most of the design and [Tushar](https://github.com/Tushar-4781) implemented the first screens to share privately with someone.  
<img src="/img/share_private.gif" alt="share-private" width="400"/>  

- **Small improvements that make a big difference**
🙏Thanks [Mallika](https://github.com/mallikarai05) & [Tushar](https://github.com/Tushar-4781)!! 🙏
  - Update button now a checkmark and moved to topright position
  - Added a 'color' tag that allows you to change colors  
    <img src="/img/update_checkmark.PNG" alt="update-checkmark" width="400"/>  
  - Change expand goal icon to < instead of >
  - Allow goals to be added without duration
  - New color palette that works for dark 🕶️🌒 and light ☀️theme

## Invisible updates
- [Eric](https://github.com/egithinji) 
  - Implemented a continuous integration action that automatically builds the scheduler files required for the frontend.  
  In the frontend we can now run a script that automatically creates a PR request if there is a new version of the scheduler.
  - Created a separate output_formatter module that handles the formatting of the output from the task_placer for presentation to the front-end.  
  This also handles sorting in chronological order.
  - Moved the logic of converting a goal into tasks to the goal struct itself. Now the task_generator's job has been greatly simplified; it's responsible for getting all the tasks when given a number of goals. We still end up with a flat list of tasks, not a hierarchy.
  - Made it easy to adjust the time granularity as we desire.
  - Added a single integration test approach where we define tests once for testing both the Rust code internally and the resulting wasm.
  - Made repetition daily and weekly work.
  - Made time constraints after_time and before_time work.
  - Made time constraint day of the week (Mondays, Tuesdays, etc) work.
  - Removed the unwrap() statements. Created an Error type that we'll use going forward to handle various error conditions.
  - Made 'sprinkling' a multi-hour task over multiple slots possible to fill up gaps and do the maximum possible.
- [Yohanes](https://github.com/Y0h4n3s) is sharing his Rust expertise with us to improve the scheduler. Welcome! 👐
- ✨New screen designs✨ for improving the experience and sharing privately in the make...  
- [Tushar](https://github.com/Tushar-4781) revamped the components for the new edit-in-place and add goals from archive/public without leaving the screen.
- Added tests  
- Fixed bugs  
<br />  
## Wishing you all the best!
<br />
<br />

Have an idea to improve ZinZen®?  
Please [give us feedback](https://zinzen.me/Home/ZinZen/Feedback).

