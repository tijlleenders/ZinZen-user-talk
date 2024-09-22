Seven months update  
UI improvements...
[Read more...](https://blog.zinzen.me/2024/09/15/App-update.html)   

@Testers: 🙏**THANK YOU**🙏 !  
@All users: Please use [the feedback page](https://zinzen.me/Feedback).

Special thanks to the community of contributors who volunteer their time and skills to ZinZen®.
  
- [Tushar](https://github.com/Tushar-4781)
- [Vinay](https://github.com/vinaybadgujar102) 
- [Jayanth Parthsarathy](https://github.com/Jayanth-Parthsarathy)
- [Mehedi Hasan](https://github.com/mehedihasan2810)
- [Shubham-Praj](https://github.com/Shubham-Praj)
- [Nicholas-Kipkoech](https://github.com/Nicholas-Kipkoech)

## Big visible updates 🎁🎁🎁

- **✨Scheduler updates✨**  
Announced in last update: the auto-scheduling killer feature is revealing itself:  
  - Rewritten from scratch in a simpler way by using <Rc> for counting conflicts
  - Respect the selected days filter
  - Respect minimum and maximum daily/week Budgets
  - Include simple subGoals for a Budget and count that towards the Budget, but only if the subGoal has a duration
    It will fill up the remaining budget using the Budget name
  - Allow users to set 0 as minimum budget value
  - Scheduler can handle Goal.start < Calendar.start
  - Goals without a deadline no longer considered impossible
  - Still works if every time slot for a Goal overlaps with other Goals
  - Handles tasksCompleted today to make sure they don't "shift" when input changes
<video width="320" height="240" controls>
  <source src="/img/Work_budget_with_subgoal.gif" type="video/gif">
Your browser does not support the video tag.
</video>

- **Some more scheduler fanciness**
  - Postpone a Task from the UI
<video width="320" height="240" controls>
  <source src="/img/Reschedule.gif" type="video/gif">
Your browser does not support the video tag.
</video>


- **✨Basic version of hints✨**
  - Want something - but no idea on how to proceed?  
    Use the ZinZen® social search engine to get suggestions!
  - It will remember which hints you deleted, so you don't see them again.
  - If you like the hint, add them to your Goals with two clicks.
  <img src="/img/Hints.png" alt="hints" width="400"/>

- **Instant Drag & Drop**
  - No need to 'loooong press' anymore to drag!
<video width="320" height="240" controls>
  <source src="/img/Drag.gif" type="video/gif">
Your browser does not support the video tag.
</video>



- **Add Phone number bookmarks**
  - Soft delete: no more accidentally deleting a whole tree of Goals forever...
<video width="320" height="240" controls>
  <source src="/img/Phone_links.gif" type="video/gif">
Your browser does not support the video tag.
</video>

- **Visual hint goal navigation**  
  - Added a visual hint to easily find the goal you're navigating to from MyTime screen. If it's in a long list this can be hard.
<video width="320" height="240" controls>
  <source src="/img/Goal_navigate_highlight.gif" type="video/gif">
Your browser does not support the video tag.
</video>


- **Visual help in goal navigation**
  - Soft delete: no more accidentally deleting a whole tree of Goals forever...
<video width="320" height="240" controls>
  <source src="/img/Soft_delete.gif" type="video/gif">
Your browser does not support the video tag.
</video>


- **Partner mode**
  - More intuitive flow for a sharing, and seeing your Partner's goals
    <video width="320" height="240" controls>
  <source src="/img/Sharing.gif" type="video/gif">
Your browser does not support the video tag.
</video>

- **🚤 Faster navigation 🏃‍♀️**
  - Navigate to subGoals with one click, instead of two.
  - The Goal summary, previously shown after first click, is now shown on the second screen.
<video width="320" height="240" controls>
  <source src="/img/Fast_navigation.gif" type="video/gif">
Your browser does not support the video tag.
</video>

  

- **Strike through done goals**
  - Cross-out remains visible.  
    The Goal will only move to Trash once you navigate away.  
    This is much nicer for shopping lists. It avoids Goals jumping around in the list, and you get to enjoy the satisfaction of getting things done a bit longer :).
<video width="320" height="240" controls>
  <source src="/img/Cross_out.gif" type="video/gif">
Your browser does not support the video tag.
</video>


## **Small improvements that make a big difference**
  -	Increased font size for readability in language selection screen
  - Better wording in share goal modal
  - Explained the Partner page when first viewing it
  - No budget is possible if any of ancestors is a Goal with a duration
  - Made it impossible to define an unrealistic budget
  - Improved README.md
  - Show ! in Goal lists when scheduler says it's impossible
  - Make edit modal 'stick' right above keyboard
  - Fix between slider not working properly in Budget edit modal
  - Fix error importing mp3 assets
  - Show error message on screen when Scheduler breaks
  - Fix Goal budget summary not showing up
  - Removed auto-capitalization of Goal titles
  - Made tapping ZinZen® logo topleft easier by increasing tap area
  - Trashed goals older than 7 days will automatically delete forever
  - Keyboard support for intro screens and adding goals
  - See build and version number on Feedback page
  - Fix sorting subGoals
  - Fast-add a Goal from the MyTime page directly
  - Show a confirmation message when you update a Goal
  - Added instructions for responsible disclosure of security issues
  - Made the star selection on Feedback page clearer

## Invisible updates
  - Separate list of attribute (inheritance) for Goals vs Budgets
  - Update Playwright to support node 20
  - Bump wasm-bindgen, Vite, React and other dependencies versions
  - Removed inheritance of Budget properties by subGoals
  - Removed Webpack dependencies
  - Fixed unrealistic starter goals
  - Revamped Journal page and added infinite scrolling
  - Ported all Cypress tests to Playwright
  - Fix persisting confirmation state
  - Fixed integration issues between UI an Scheduler
  - Scheduler doesn't get send irrelevant/old notOn blocks
  - Changed Goal storage in preparation for Move feature

<br />
  
## Wishing you all the best!  
<br />
<br />

Please help improve [ZinZen](https://zinzen.me)®:  
- [Donate](https://donate.stripe.com/6oE4jK1iPcPT1m89AA)
- [Give us feedback](https://zinzen.me/Feedback)
- Contribute to the [GitHub project](https://github.com/tijlleenders/ZinZen) with code, feature requests, idea's, translations, documentation or artwork  
- Tip friends about us!

## Comments  
Post comments anonymously via [this feedback form](https://zinzen.me/Feedback)  

