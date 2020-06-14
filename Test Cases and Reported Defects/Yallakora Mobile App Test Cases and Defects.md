# Test cases for "Splash" screen #
<table>
    <tr>
        <td>Test Case ID</td>
        <td>Test Priority</td>
        <td>Module Name</td>
        <td>Test Case Title</td>
        <td>Pre-conditions/Test Data</td>
        <td>Test Step</td>
        <td>Expected Result</td>
        <td>Actual result</td>
        <td>Status (Pass, Fail, Not Executed, Blocked, On Hold)</td>
        <td>Test Case designed by</td>
    </tr>
    <tr>
        <td>YK_001</td>
        <td>High</td>
        <td>Splash screen</td>
        <td>Splash Screen - Verify UI of "Splach" screen_UI</td>
        <td>Internet connection (Wi-Fi/Mobile data)</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app 3- Check "Splash" screen UI</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed 3- "Splash" screen UI should be as in UI document</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_002</td>
        <td>Low</td>
        <td>Splash screen</td>
        <td>Splash Screen - Check app behavior in case of tapping on "Splash" screen while loading_Functional</td>
        <td>Internet connection (Wi-Fi/Mobile data)</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app 3- Tap on "Splash" screen while loading</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed 3- No action should occur</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
</table>

# Test cases for "Main" screen #

<table>
    <tr>
        <td>Test Case ID</td>
        <td>Test Priority</td>
        <td>Module Name</td>
        <td>Test Case Title</td>
        <td>Pre-conditions/Test Data</td>
        <td>Test Step</td>
        <td>Expected Result</td>
        <td>Actual result</td>
        <td>Status (Pass, Fail, Not Executed, Blocked, On Hold)</td>
        <td>Test Case designed by</td>
    </tr>
    <tr>
        <td>YK_003</td>
        <td>High</td>
        <td>Main screen</td>
        <td>Main Screen - Verify UI of "Main" screen_UI</td>
        <td>Internet connection (Wi-Fi/Mobile data)</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Check "Splash" screen UI</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Main" screen UI should be as in UI document</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_004</td>
        <td>High</td>
        <td>Main screen</td>
        <td>Main Screen - Check functionality of swipe left and right in news carousel _Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data)2- Two or more news retrieved
	</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app 3- Swipe between the displayed news</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- In case of: Swipe left: Next news should be displayed Swipe right: Previous news should be displayed</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_005</td>
        <td>High</td>
        <td>Main screen</td>
        <td>Main Screen - Check functionality of tapping on any displayed news_Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- one or more news retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app 3- Tap on the first news in the news carousel</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- User should be navigated to "News details" screen</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_006</td>
        <td>Low</td>
        <td>Main screen</td>
        <td>Main Screen - Check app behavior in case internet connection is down while scrolling in the screen_Functional</td>
        <td>Internet connection (Wi-Fi/Mobile data)</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app 3- Scroll down in "Main" screen 4- Disconnect WiFi network 5- Continue Scrolling </td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- All screen data should be loaded and displayed 4- No network should be connected 5- "No internet connection" error screen should not be displayed and user should be able to scroll up and down while all data are displayed successfully</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_007</td>
        <td>Medium</td>
        <td>Main screen</td>
        <td>Main Screen - Check the functionality of tapping on physical home button while in "Main" screen_Functional</td>
        <td> Internet connection (Wi-Fi/Mobile data)</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app 3- Tap on physical home button</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- App should goes into the background</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
</table>

# Test cases for "Matches" screen #

<table>
    <tr>
        <td>Test Case ID</td>
        <td>Test Priority</td>
        <td>Module Name</td>
        <td>Test Case Title</td>
        <td>Pre-conditions/Test Data</td>
        <td>Test Step</td>
        <td>Expected Result</td>
        <td>Actual result</td>
        <td>Status (Pass, Fail, Not Executed, Blocked, On Hold)</td>
        <td>Test Case designed by</td>
    </tr>
    <tr>
        <td>YK_008</td>
        <td>High</td>
        <td>Matches screen</td>
        <td>Matches screen - Check functionality of "Play" icon at the top right of the screen_Functional </td>
        <td>Internet connection (Wi-Fi/Mobile data)</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Matches" 4- Tap on "Play" icon at the top right of the screen</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Matches" screen should be displayed  4- "Live matches" pop-ups</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_009</td>
        <td>Low</td>
        <td>Matches screenscreen</td>
        <td>Matches screen - Check functionality of tapping on any item in the screen while "All matches" list expanded_Functional </td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- One or more matches</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Matches" 4- Tap on "All games" expandable list 5- Tap on any other clickable item in the dimmed screen</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Matches" screen should be displayed  4- "All games" list will be expanded 5- No action should occur except collapse arrow</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_010</td>
        <td>Low</td>
        <td>Matches screenscreen</td>
        <td>Matches screen - Check functionality of tapping on the already selected day_Functionalal </td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- one or more matches retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Matches" 4- Tap on any day from the carousel (ex. Tuesday) 5- Tap again on the same day</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Matches" screen should be displayed  4- All matches for the selected day should be displayed 5- No action/refresh should occur </td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_011</td>
        <td>Medium</td>
        <td>Matches screenscreen</td>
        <td>Matches screen - Check "All games" expandable list in case of no matches_Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- No matched retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Matches" 4- Tap on "All games" expandable list</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Matches" screen should be displayed  4- Info message should be displayed to inform the user that there is not matches for today</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_012</td>
        <td>High</td>
        <td>Matches screen</td>
        <td>Matches screen - Check functionality of navigating arrows in calendar_Functional</td>
        <td> Internet connection (Wi-Fi/Mobile data)</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Matches" 4- Tap on "Calender" icon at the top right of the screen 5- Tap on left and right arrows</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Matches" screen should be displayed  4- Calender should be displayed 5- In case of tapping on: Left arrow: Next month should be displayed Right arrow: Previous Month should be displayed</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
</table>

# Test cases for "Championships" screen #

<table>
    <tr>
        <td>Test Case ID</td>
        <td>Test Priority</td>
        <td>Module Name</td>
        <td>Test Case Title</td>
        <td>Pre-conditions/Test Data</td>
        <td>Test Step</td>
        <td>Expected Result</td>
        <td>Actual result</td>
        <td>Status (Pass, Fail, Not Executed, Blocked, On Hold)</td>
        <td>Test Case designed by</td>
    </tr>
    <tr>
        <td>YK_013</td>
        <td>Medium</td>
        <td>Championships screen</td>
        <td>Championships screen - Championship details screen - Check functionality of "Back" button and physical back button _Functionality </td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- One or more championship retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Championships" 4- Tap on any item from the displayed list 5- Tap on "Back" button</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Championships" screen should be displayed  4- "Champtionship details" screen should be displayed 5- User should be navigated back to "Championships" screen</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_014</td>
        <td>High</td>
        <td>Championships screen</td>
        <td>Championships screen - Championship details screen - Check functionality of tapping on statistics_Functionality </td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- One or more championship retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Championships" 4- Tap on any item from the displayed list 5- Tap on "Statistics"</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Championships" screen should be displayed  4- "Champtionship details" screen should be displayed 5- User should be navigated back to "Statistics" screen</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_015</td>
        <td>Medium</td>
        <td>Championships screen</td>
        <td>Championships screen - Championship details screen - Statistics screen - Check functionality of swiping right_Functionality </td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- One or more championship retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Championships" 4- Tap on any item from the displayed list 5- Tap on "Statistics" 6- Swipe right</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Championships" screen should be displayed  4- "Champtionship details" screen should be displayed 5- User should be navigated back to "Statistics" screen 6-  "Champtionship details" screen should be displayed</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_016</td>
        <td>High</td>
        <td>Championships screen</td>
        <td>Championships screen - Championship details screen - News screen - Make sure that the displayed news are related to the selected championship _Functionality </td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- One or more championship retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Championships" 4- Tap on any item from the displayed list 5- Tap on "News" 6- Verify the displayed news</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Championships" screen should be displayed  4- "Champtionship details" screen should be displayed 5- User should be navigated back to "Statistics" screen 6- All the displayed news should be related to the selected championship</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
</table>

# Test cases for "Your Teams" screen #

<table>
    <tr>
        <td>Test Case ID</td>
        <td>Test Priority</td>
        <td>Module Name</td>
        <td>Test Case Title</td>
        <td>Pre-conditions/Test Data</td>
        <td>Test Step</td>
        <td>Expected Result</td>
        <td>Actual result</td>
        <td>Status (Pass, Fail, Not Executed, Blocked, On Hold)</td>
        <td>Test Case designed by</td>
    </tr>
    <tr>
        <td>YK_017</td>
        <td>High</td>
        <td>Your Teams screen</td>
        <td>Your Teams screen - Check UI in case of no added favorite teams_UI</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- No favorite teams added</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Your Teams" while there is no added favorite teams</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Your Teams" screen UI should be as in UI document containing logo, info message and a button to add favorite teams</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_018</td>
        <td>High</td>
        <td>Your Teams screen</td>
        <td>Your Teams screen - Make sure that when user relaunch the app all favorite teams saved are displayed_Functional </td>
        <td>Internet connection (Wi-Fi/Mobile data)</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Your Teams"  4- Tap on "Add" icon at the top right of the screen 5- Select champtionship 6- Select team and tap on "Agree" button 7- Close the app 8- Open the app again 9- Tap on "Your Teams" </td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Your Teams" screen should be displayed 4- List of championships should be displayed 5- List of Teams inside the selected champtionship should be displayed 6- User will be navigated to "Your Teams" screen with the selected favorite team displayed 7- App should be closed 8- "Splash" screen should be displayed, then "Main" screen should be displayed 9- The selected favorite team should displayed in "Your Teams" screen</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_019</td>
        <td>Low</td>
        <td>Your Teams screen</td>
        <td>Your Teams screen - Make sure that user can not select already added favorite team from another championship_Functional </td>
        <td>Internet connection (Wi-Fi/Mobile data)</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Your Teams"  4- Tap on "Add" icon at the top right of the screen 5- Select champtionship 6- Select team and tap on "Agree" button 7- Tap on "Add" icon at the top right of the screen 8- Select another champtionship containing your favorite team added 9- Check the favorite team added in the list of teams</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Your Teams" screen should be displayed 4- List of championships should be displayed 5- List of teams inside the selected champtionship should be displayed 6- User will be navigated to "Your Teams" screen with the selected favorite team displayed 7- List of championships should be displayed 8- List of teams inside the selected champtionship should be displayed 9- The already added favorite team is selected</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_020</td>
        <td>High</td>
        <td>Your Teams screen</td>
        <td>Your Teams screen - Edit your teams screen - Check functionality of delete icon_Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- One or more news retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "Your teams"  4- Tap on "Edit" icon at the top right of the screen 5- Tap on "Delete" icon</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "Your Teams" screen should be displayed 4- "Edit your teams" screen should be displayed containing all added favorite teams 5- Team should be deleted from the list and from the list in "Your team" screen </td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
</table>

# Test cases for "News" screen #

<table>
    <tr>
        <td>Test Case ID</td>
        <td>Test Priority</td>
        <td>Module Name</td>
        <td>Test Case Title</td>
        <td>Pre-conditions/Test Data</td>
        <td>Test Step</td>
        <td>Expected Result</td>
        <td>Actual result</td>
        <td>Status (Pass, Fail, Not Executed, Blocked, On Hold)</td>
        <td>Test Case designed by</td>
    </tr>
    <tr>
        <td>YK_021</td>
        <td>High</td>
        <td>News screen</td>
        <td>News Screen - Check functionality of swipe left and right in news carousel _Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- Two or more news retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "News" screen 4- Swipe between the displayed news</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "News" screen should be displayed 4- In case of: Swipe left: Next news should be displayed Swipe right: Previous news should be displayed</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_022</td>
        <td>High</td>
        <td>News screen</td>
        <td>News Screen - Check functionality of tapping on "Another sports" button_Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- Two or more news retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "News" screen 4- Tap on "Another sports"</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "News" screen should be displayed 4- "Another sports" screen should be displayed</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_023</td>
        <td>Low</td>
        <td>News screen</td>
        <td>News Screen - Make sure that when user scroll down in the news list no clashing occur with the "Latest news" and "Another sports" buttons_UI</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- one or more news retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "News" screen 4- Scroll down and check "Latest News" and "Another sports" buttons position</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "News" screen should be displayed 4- No clashing should occur between the buttons and the list of news</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_024</td>
        <td>High</td>
        <td>News screen</td>
        <td>News Screen - News details screen - Make sure that the app share the correct URL in case of sharing any news_Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- one or more news retrieved</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app and wait till splash screen timeout 3- Tap on "News" screen 4- Tap on any News 5- Tap on "Share" icon at the top right of the screen 6- Select any app to share the news through 7- Tap on the shared news URL</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- "News" screen should be displayed 4- "News Details" screen should be displayed 5- Platfrom sharing window displayed 6- News URL should be generated and shared 7- User should be navigated to the shared news on "Yallakora" website</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

# Test cases for Push Notification #

<table>
    <tr>
        <td>Test Case ID</td>
        <td>Test Priority</td>
        <td>Module Name</td>
        <td>Test Case Title</td>
        <td>Pre-conditions/Test Data</td>
        <td>Test Step</td>
        <td>Expected Result</td>
        <td>Actual result</td>
        <td>Status (Pass, Fail, Not Executed, Blocked, On Hold)</td>
        <td>Test Case designed by</td>
    </tr>
    <tr>
        <td>YK_025</td>
        <td>High</td>
        <td>Push Notification</td>
        <td>Push notification - Verify UI of the app notification in notification center _UI</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- One or more notification</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Send push notification 3- Open notification center and check notification UI</td>
        <td>1- Internet should be connected successfully 2- Notification should be sent successfully to the selected users 3- The received notification UI should be as in UI document containing clear title and brief</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_026</td>
        <td>High</td>
        <td>Push Notification</td>
        <td>Push Notification - Make sure that all notifications remain displayed as long as it is not removed or opened_Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- One or more news notification</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Send several push notifications 3- Open notification center and check all notifications received </td>
        <td>1- Internet should be connected successfully 2- Notifications should be sent successfully to the selected users 3- All received notifications should be grouped and remains displayed till user open them</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_027</td>
        <td>High</td>
        <td>Push Notification</td>
        <td>Push Notification - Check functionality of tapping on notification from notification center_Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- One or more notification</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Send push notifications 3- Open notification center and tap on any notification received </td>
        <td>1- Internet should be connected successfully 2- Notifications should be sent successfully to the selected users 3- User should be navigated to the "News Details" screen of the selected notification</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
</table>

# Mobile application generic test cases #

<table>
    <tr>
        <td>Test Case ID</td>
        <td>Test Priority</td>
        <td>Module Name</td>
        <td>Test Case Title</td>
        <td>Pre-conditions/Test Data</td>
        <td>Test Step</td>
        <td>Expected Result</td>
        <td>Actual result</td>
        <td>Status (Pass, Fail, Not Executed, Blocked, On Hold)</td>
        <td>Test Case designed by</td>
    </tr>
    <tr>
        <td>YK_028</td>
        <td>Medium</td>
        <td>Generic</td>
        <td>Generic - Check that the app is adaptable to different mobile platforms_Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- iOS, Android devices"</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app using iOS platform and Android platform 3- Check app compatibility in both platforms"</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- The application should be compatible with any platform"</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_029</td>
        <td>Medium</td>
        <td>Generic</td>
        <td>Generic - Check the app performance while connecting to different internect networks_Functional</td>
        <td>Internet connection (Wi-Fi, 3G, 4G) "</td>
        <td>1- Connect to internet (Wi-Fi, 3G, 4G) 2- Open "Yallakora" app 3- Check app performance in all three different networks"</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- The application should be functioning smoothly running on any network type"</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_030</td>
        <td>High</td>
        <td>Generic</td>
        <td>Generic - Make sure that loading time for all screens is not taking too long_Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- one or more news retrieved "</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app 3- Tap on any news in the news carousel in "Main" screen 4- Check loading time"</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- User should be navigated to "News Details" screen 4- Navigation from screen to screen loading time should not take too long"</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_031</td>
        <td>High</td>
        <td>Generic</td>
        <td>Generic - Check that the app is working as expected after updating the app version_Functional</td>
        <td>1- Internet connection (Wi-Fi/Mobile data) 2- New update available "</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Update "Yallakora" app 3- Open the app after updating successfully"</td>
        <td>1- Internet should be connected successfully 2- The app should be updated successfully and ready to launch 3- The app should be working as expected, "Splash" screen should be displayed, then "Main" screen should be displayed"</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_032</td>
        <td>High</td>
        <td>Generic</td>
        <td>Generic - Check how the app coreespond to changing display mode (Landscape, and portrait)</td>
        <td>Internet connection (Wi-Fi/Mobile data)</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Set display mode to portrait then open "Yallakora" app 3- Set display mode to landscape and navigate back to "Yallkora" app"</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed in portrait mode, and all screens should be displayed in portrait mode as well 3- All screens should remain displayed in portrait mode"</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
    <tr>
        <td>YK_033</td>
        <td>Medium</td>
        <td>Generic</td>
        <td>Generic - Check the app behavior in case of relaunch from the inactive mode or after receiving a call_Functional</td>
        <td>Internet connection (Wi-Fi/Mobile data)</td>
        <td>1- Connect to internet (WiFi/Mobile data) 2- Open "Yallakora" app 3- Tap on any news in the news carousel in "Main" screen 4- Answer a phone call 5- Navigate back to app"</td>
        <td>1- Internet should be connected successfully 2- "Splash" screen should be displayed, then "Main" screen should be displayed 3- User should be navigated to "News details" screen 4- The app should goes into the background 5- "News details" screen should remain displayed in case of timeout didn't occur"</td>
        <td>Not yet executed</td>
        <td>Not Executed</td>
        <td>Hadeel</td>
    </tr>
</table>

# Bug Report #

<table>
    <tr>
        <td>Clear title</td>
        <td>Reproduce steps</td>
        <td>Needed attachments</td>
        <td>Affected devices</td>
        <td>Network</td>
        <td>Severity</td>
        <td>Prority</td>
    </tr>
    <tr>
        <td>Your teams screen - Choose your favorite team screen - In case of searching for a non existing item no info message displayed_Functional</td>
        <td>App version: 5.36 iOS version: 13.5  Pre-requisite: 1- Internet connection  Steps: 1- Open "Yallakora" app 2- Tap on "فريقك" from bottom bar 3- Tap on "+" icon at the top right of the screen 4- Tap on search bar 5- Insert "Test" in the search bar   Actual result: Nothing displayed  Expected result: Info message to clarify that there is no item found  * Check the attached screenshot</td>
        <td>https://ibb.co/fYfFXB3</td>
        <td>iPhone 11 Pro Max</td>
        <td>WiFi and Mobile data</td>
        <td>Low</td>
        <td>Low</td>
    </tr>
    <tr>
        <td>Your teams screen - Choose your favorite team screen - Search bar disclaimer in leagues list is misleading_Usability</td>
        <td>App version: 5.36 iOS version: 13.5  Pre-requisite: 1- Internet connection  1- Open "Yallakora" app 2- Tap on "فريقك" from bottom bar 3- Tap on "+" icon at the top right of the screen 4- Check search bar disclaimer  Actual result: Search bar disclaimer "بحث عن فرقة او منتخب"  Expected result: Search bar should contain descriptive disclaimer to the functionality of it "بحث عن بطولة"  * Check the attached screenshot</td>
        <td>https://ibb.co/4FddD18</td>
        <td>iPhone 11 Pro Max</td>
        <td>WiFi and Mobile data</td>
        <td>Low</td>
        <td>Medium</td>
    </tr>
    <tr>
        <td>Your teams screen - Choose your favorite team screen - Back button is missing_Functional</td>
        <td>App version: 5.36 iOS version: 13.5  Pre-requisite: 1- Internet connection  Steps: 1- Open "Yallakora" app 2- Tap on "فريقك" from bottom bar 3- Tap on "+" icon at the top right of the screen  Actual result: No back button displayed  Expected result: Back button should be displayed at the top left of the screen   * Check the attached screenshot</td>
        <td>https://ibb.co/dbMLqwm</td>
        <td>iPhone 11 Pro Max</td>
        <td>WiFi and Mobile data</td>
        <td>Low</td>
        <td>Low</td>
    </tr>
    <tr>
        <td>Your teams screen - App freeze when user add specific items from teams list_Functional</td>
        <td>App version: 5.36 iOS version: 13.5  Pre-requisite: 1- Internet connection 2- Leagues and teams are successfully retrieved  Steps: 1- Open "Yallakora" app 2- Tap on "فريقك" from bottom bar 3-Tap on "كأس مصر"  4- Select "أبو قير للاسمدة"  Actual result: App freeze  Expected result: The selected team should be selected successfully  Note: Same issue occur in case of tapping on the same specific teams in "Championships" screen * Check the attached recorded video</td>
        <td>https://vimeo.com/428356285</td>
        <td>iPhone 11 Pro Max</td>
        <td>WiFi and Mobile data</td>
        <td>High</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Matches screen - App crashes when user taps on "Play" icon after navigating from "Your teams" screen_Functional</td>
        <td>App version: 5.36 iOS version: 13.5  Pre-requisite: 1- Internet connection  Steps: 1- Open "Yallakora" app 2- Tap on "مباريات" from bottom bar 3- Tap on "فريقك" from bottom bar 4- Tap on "مباريات" from bottom bar again 5- Tap on play icon at the top right of the screen  Actual result: App crashes  Expected result: "Live Matches" screen should be displayed successfully  * Check the attached recorded video</td>
        <td>https://vimeo.com/428346316</td>
        <td>iPhone 11 Pro Max</td>
        <td>WiFi and Mobile data</td>
        <td>High</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Champtionships screen - Championship details screen - Long titles are trimmed from the beginning of the statement_UI</td>
        <td>App version: 5.36 iOS version: 13.5  Pre-requisite: 1- Internet connection 2- Championship with more than 29 character  Steps: 1- Open "Yallakora" app 2- Tap on "بطولات" from bottom bar 3- Scroll down 4- Tap on "كأس محمد السادس للأندية الابطال" from bottom bar 5- Check screen title  Actual result: Title trimmed from the beginning of the statement  Expected result: Title should not be trimmed   * Check the attached screenshot</td>
        <td>https://ibb.co/WtjgtVP</td>
        <td>iPhone 11 Pro Max</td>
        <td>WiFi and Mobile data</td>
        <td>Low</td>
        <td>Low</td>
    </tr>
    <tr>
        <td>News details screen/ Push Notification - No action occurs in case of user tap on any notification from notification center while in "News details" screen_Functional</td>
        <td>pp version: 5.36 iOS version: 13.5  Pre-requisite: 1- Internet connection 2- two notifications  Steps: 1- Open "Yallakora" app 2- Tap first notification from notification center 3- While in "News details" tap on the second notification in notification center   Actual result: No action occurs, the same news is still displayed   Expected result: User should be navigated to the new news details screen  Same issue occur in case of tapping on any notification from notification center while in "News detaisl" screen  * Check the attached video</td>
        <td>https://vimeo.com/428851186</td>
        <td>iPhone 11 Pro Max</td>
        <td>WiFi and Mobile data</td>
        <td>Medium</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Your teams screen - When virtual keyboard is displayed, user is not able to see the full list of championships_Functional</td>
        <td>App version: 5.36 iOS version: 13.5 Pre-requisite: 1- Internet connection 2- 25 or more champtionships  Steps: 1- Open "Yallakora" app 2- Tap on "Your teams" 3- Tap on "Add" icon at the top right of the screen 4- Tap on search bar 5- Scroll till the end of the list  Actual result: Any championship after the 25th is hidden under the virtual keyboard  Expected result: All list should be displayed, virtual keyboard should not hide any item  * Check the attached video</td>
        <td>https://vimeo.com/428834129</td>
        <td>iPhone 11 Pro Max</td>
        <td>WiFi and Mobile data</td>
        <td>Low</td>
        <td>Medium</td>
    </tr>
    <tr>
        <td>Your teams screen -  Minor spelling mistake in the info message  displayed in case of no added favorite team_Functional</td>
        <td>App version: 5.36 iOS version: 13.5 Pre-requisite: 1- Internet connection 2- No added favorite team  Steps: 1- Open "Yallakora" app 2- Tap on "Your teams" 3- Check the text displayed  Actual result: "ابداً" is not the right word  Expected result: The word should be changed to "ابدأ"   * Check the attached screenshot</td>
        <td>https://ibb.co/hVyRngW</td>
        <td>iPhone 11 Pro Max</td>
        <td>WiFi and Mobile data</td>
        <td>Low</td>
        <td>Medium</td>
    </tr>
</table>