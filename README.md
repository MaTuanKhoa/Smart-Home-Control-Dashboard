# Smart-Home-Control-Dashboard
.NET MAUI Project

Project Title 
Smart Home Control Dashboard (Single Screen UI) 

Project Objective 
Design a single-page dashboard UI using .NET MAUI + XAML that visually represents the control 
panel of a smart home. The focus is on layout, visual hierarchy, reusable components, and 
responsive design, not application logic. 

Scope & Constraints 
Single screen only 
XAML-focused layout & styling 

UI Requirements 
1. Screen Layout 
Use Grid + StackLayout / VerticalStackLayout
------------------------------------------------- 
| Header: Smart Home Dashboard       | 
|-----------------------------------------------| 
|  Weather Card (Temp, Icon, Status)    | 
|-----------------------------------------------| 
Device Control Cards (2 x 2 Grid)                                                                                                                                                                             | - Light
| - Fan
| - Air Conditioner
| - Security
|---------------------------------------------- | 
Energy Usage Summary                          
| ------------------------------------------------- |

2. Header Section 
App title 
Subtitle (e.g. “Living Room Overview”) 
Optional icon (Image) 
XAML concepts practiced:
  - Grid column layout 
  - FontSize, FontAttributes 
  - Margin & Padding 

3. Information Card (Weather / Status) 
Rounded card using Frame or Border 
Icon + text 
Soft shadow 
XAML concepts practiced:
  - Frame / Border 
  - CornerRadius 
  - HorizontalStackLayout 
  - Image + Label alignment 

4. Device Control Cards (Main Focus) 
+ Create 4 reusable UI cards, each with:
  - Icon 
  - Device name 
  - Status label (ON / OFF) 
  - Toggle Switch (UI only, no logic) 
Layout: Grid with 2 columns × 2 rows 
XAML concepts practiced:
  - Grid row/column definitions 
  - Switch control 
  - Consistent spacing 
  - Visual hierarchy 

5. Energy Usage Summary
  - ProgressBar (e.g. “Today’s Energy Usage”) 
  - Percentage label 
+ XAML concepts practiced: 
  - ProgressBar
  - Label alignment
  - StackLayout spacing 
+ Styling Requirements
  - Use ResourceDictionary for: 
    * Colors 
    * Font sizes 
  - Define: 
    * Primary color 
    * Secondary color 
+ XAML concepts practiced:
  - StaticResource 
  - Consistent theming 
+ Expected Deliverables
  - MainPage.xaml 
  - MainPage.xaml.cs (empty or minimal) 
  - Clean, readable XAML 
  - Responsive layout (works on phone & tablet) 
+ Time Breakdown (3 Hours) 
Task Time
  - Layout skeleton (Grid + sections)   45 min 
  - Device cards UI                     60 min
  - Styling & spacing                   45 min 
  - Polish & alignment                  30 min 
+ Learning Outcomes 
  - After completing this project, the student will be able to:
  - Design a complex single-page UI in MAUI 
  - Use Grid effectively 
  - Apply consistent styling via resources 
  - Build card-based layouts commonly used in real apps 
