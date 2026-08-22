# anti-khanmigo-reimagined
uBlock Origin/AdBlock Plus filter to block Khanmigo crap on school accounts. Normally impossible to disable, as the settings page says that it can't be managed by people under 18. 

> [!WARNING]
> **USE AT YOUR OWN RISK!** If you're modifying settings on a school device, I assume no responsibility for it or any trouble you might get into as a result. This is primarily intended as a resource for home computers accessing school accounts (if so allowed), or schools that don't have issues with custom AdBlock filters. 

I'm still working on these filters, so not everything may be blocked yet. This is my ~~first~~ second time making a filter, so apologies if it looks duct taped together.

## Your filter choices

Khanmigo is now more integrated into the software, and some features may be required to complete assignments. Therefore, the basic filter will only block non-essential features. I hope to make another filter focusing on other AI related features, but it might hinder the ability to complete assignments. Currently, it isn't available, and I can't guarantee it ever will be. 

### Basic Filter
The basic filter is focused on blocking non-essential AI features (those which aren't needed for assignments). This includes the following:
* Khanmigo's avatar on the home screen
* "Tutor me" option in the sidebar
* Khanmigo options in the Activity History
* Option to customize Khanmigo's avatar with gems.
* Khanmigo tab in settings (where you personalize Khanmigo's voice).

### Gem Filter
Focuses on gem-related content. Specifically, it blocks:
* Gems on the top right corner of the home page
* Gems on the bottom right corner of the home page
* The gem card on the "Assignment Completed" screen
* Gem statistics on the Achievements screen.

> [!NOTE]
> This will not prevent you from earning gems or contributing to the class gem pool - it's all client side. That said, it may become more difficult to access the Customize Khanmigo page with this filter enabled. 

### Legacy Filter
> [!NOTE]
> You probably don't need to use this.

The Legacy Filter is focused on AI features in the old version of Khan Academy. This filter is no longer being updated, as this UI is mostly obsolete for students. Personal accounts still have the old UI, but they aren't forced to use Khanmigo either. 

For more info on the legacy filter, see the [old repo](https://github.com/TheRebeLiasOne/anti-khanmigo).

<details>
  <summary>Why aren't the old and new filters combined?</summary>

  Two reasons. For one, I wanted to clearly distinguish the old filter as unsupported and no longer being updated. Second, Manifest V3-based adblockers are limited in the number of custom filters they're allowed to have (thanks, Google!), so I wanted users to be able to use the least possible while still getting a full blocking experience.
</details>

## Installation

There are a couple of paths to installing this. One is much easier than the other. But first, you'll need an adblocker.

Use [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) on Firefox, or [AdGuard](https://chromewebstore.google.com/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg) on Chrome/Chromium. Both of these are free and open-source. 

<details>
  <summary><strong>Adblock Plus is not recommended.</strong> Click to see why.</summary>

  They became corporate shills. Back in the early 2010s they implemented a feature called "Acceptable Ads" and allowed large corporations to pay them to allow their ads through. It was a way to support advertising as a business model without having to deal with the incredibly annoying stuff. Sounds great!...on paper. 
  
  The reality is that all of this was (and still is) enabled on installations without the user's consent, much like how Khanmigo is forced on students regardless of whether they want to use it. Not to mention, basically saying "Hey, we're an adblocker, but we'll accept bribes to let your ads through!" is a pretty scummy practice if you ask me. 
  
  It is worth noting that the Acceptable Ads program does allow small websites/advertisers to enter for free, so it wasn't entirely biased toward rich corpos. You can also disable "Acceptable Ads" in the main settings page of ABP if you wish.
  
  There's also just the fact that they have a premium version -- and, as a matter of fact, give you ads for that as well if you don't also disable those, this time buried in the "Advanced" settings. Imagine making an adblocker and then having the audacity to throw ads into the adblocker itself. Meanwhile, uBlock Origin is not only free and open source, but its developer, Gorhill, [won't even accept donations](https://github.com/gorhill/uBlock/wiki/Why-don't-you-accept-donations%3F). 

</details>

If you're for some reason against blocking ads, you can install them and disable every filter, then just run with the ones I have. 

### Quick Install

You can use one or both of the below links to add this to your adblocker.

* [Add the Khanmigo filter](https://subscribe.adblockplus.org?location=https%3A%2F%2Fraw.githubusercontent.com%2FTheRebeLiasOne%2Fanti-khanmigo-reimagined%2Frefs%2Fheads%2Fmain%2Fanti-khanmigo-reimagined.txt&amp;title=Anti%20Khanmigo%20Reimagined)
* [Add the Gem filter](https://subscribe.adblockplus.org/?location=https%3A%2F%2Fraw.githubusercontent.com%2FTheRebeLiasOne%2Fanti-khanmigo-reimagined%2Frefs%2Fheads%2Fmain%2Fanti-khanmigo-gem-filter.txt&title=Anti%20Khanmigo%20Gems)

### Manual Installation

See the instructions for your adblocker below on manually adding the filter list. The link(s) you'll need to use are below: 

* **For the Khanmigo filter:** https://raw.githubusercontent.com/TheRebeLiasOne/anti-khanmigo-reimagined/refs/heads/main/anti-khanmigo-reimagined.txt
* **For the Gem filter:** https://raw.githubusercontent.com/TheRebeLiasOne/anti-khanmigo-reimagined/refs/heads/main/anti-khanmigo-gem-filter.txt

See instructions for:
* [uBlock Origin](https://github.com/gorhill/uBlock/wiki/Filter-lists-from-around-the-web)
* [AdGuard extension](https://adguard.com/kb/adguard-browser-extension/features/filters/#custom-filters)
* [AdBlock Plus](https://help.adblockplus.org/adblock-plus-help-center/add-or-remove-a-custom-filter)
