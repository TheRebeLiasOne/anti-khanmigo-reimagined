# anti-khanmigo-reimagined
uBlock Origin/AdBlock Plus filter to block Khanmigo crap on school accounts. Normally impossible to disable, as the settings page says that it can't be managed by people under 18. 

> [!WARNING]
> **USE AT YOUR OWN RISK!** If you're modifying settings on a school device, I assume no responsibility for it or any trouble you might get into as a result. This is primarily intended as a resource for home computers accessing school accounts (if so allowed), or schools that don't have issues with custom AdBlock filters. 

I'm still working on these filters, so not everything may be blocked yet. This is my ~~first~~ second time making a filter, so apologies if it looks duct taped together.

## Your filter choices

I've had to separate this into two filter list choices. Khanmigo is now more integrated into the software, and some features may be required to complete assignments.  

### Basic Filter: What It Blocks
The basic filter is focused on blocking non-essential AI features (those which aren't needed for assignments). This includes the following:
* Khanmigo's avatar on the home screen
* "Tutor me" option in the sidebar
* Khanmigo options in the Activity History
* Option to customize Khanmigo's avatar with gems.
* Khanmigo tab in settings (where you personalize Khanmigo's voice. 

## Advanced Filter
> [!CAUTION]
> This may block features required for assignments within Khan Academy. You have been warned.

An advanced filter is planned to hide as many AI elements as possible, with the caveat that it might hide features that are required for assignments. Release date TBA.

## Installation

> [!TIP]
> This extension only filters Khanmigo. If you want to strip AI from other websites, see check out Fanboy's AI suggestions list. To add it, use the directions for your blocker below, and also add https://github.com/easylist/easylist/blob/master/fanboy-addon/fanboy_ai_suggestions.txt. 

### uBlock Origin
> [!NOTE]
> These instructions won't work on uBlock Origin Lite.
1. Click on the extension in your toolbar, and from the popout, click the cogwheels.
2. Navigate to "filter lists" (not "my filters") tab.
3. Scroll to the bottom and click "Import".
4. Paste the link: 
6. Click "Apply Changes".
7. You're done! It should show up in the "Custom" section on the filters page.
8. You don't need to add Fanboy's list manually as it's already included under "EasyList - Annoyances". Just enable it from there. You'll manually add this to the other extensions though. 

**To update:** Should update automatically. If you ever wish to check, navigate to the filters page and find the filter in your list then click the clock icon. (If there's a loading icon, it's already in the process of updating). 

### AdGuard
1. Open AdGuard. From the extension popout, click the cogwheel.
2. On the left, click "Filters".
3. Scroll to the bottom and enable "Custom".
   *If prompted to allow user scripts*: Click the link to your browser's extension settings and toggle "Allow User Scripts".
5. Now click on "Custom", and choose "Add Custom Filter".
6. Paste  and click "Next".
7. Check the "Trusted" box if desired, then click "Add".
8. You're Done! The filter should appear in the custom list.

**To update:** open the extension popout then click the clockwise arrows at the top to check (it'll check for all enabled filters). If it's already checked, it may show as a green up arrow instead. AdGuard might not automatically install updates so it's important to check every once in a while.

### AdBlock Plus
> [!NOTE]
> Adblock Plus isn't recommended. For more info on why, see: . ABP instructions are included for convenience as it is the default at my school. 

1. Click on the extension and click the cogwheel (settings) icon in the popout.
2. On the left of the page, choose "Advanced".
3. Scroll down and click "Add Filter List by URL".
4. Paste the link: , then choose "Add a Filter List". 
6. You're done! It should be in the list alongside the default filters.

**To update:** Revisit the "Advanced" page and find the filter, then click the cogwheel (settings) icon next to the filter and choose "Update Now". 
