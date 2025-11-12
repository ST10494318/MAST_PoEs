MAST PROJECT 

Repo link:
[https://github.com/ST10494318/MAST_Part_2.git](https://github.com/ST10494318/MAST_PoEs.git)

Video link :
https://youtu.be/rHWBnXARrYA

Changelog - Christoffel's Menu App
Project Overview
A React Native restaurant menu management application with course filtering and item management capabilities.

Changes Made
1. Initial Project Setup
   
Set up React Native project structure with TypeScript

 Implemented navigation using React Navigation Stack

 Created base types and interfaces in types.ts

2. Core Application Structure
   
 App.tsx: Configured navigation stack with 3 main screens

 HomeScreen: Main dashboard with complete menu display

 AddMenuItemScreen: Form for adding new menu items

 FilterByCourseScreen: Filtering and statistics by course

3. Data Model & Types
   
 Defined MenuItem interface with properties:

id: string

name: string

description: string

course: string

price: number

 Defined COURSES constant: ['Starter', 'Main', 'Dessert', 'Side', 'Drink']

4. Home Screen Features
   
 Complete menu display in FlatList

 Real-time statistics: Total menu items count

 Average price calculation per course

 Remove item functionality with confirmation alerts

 Navigation to Add and Filter screens

5. Add Menu Item Screen
   
 Form validation for all fields

Course selection via Picker component

 Price input with numeric validation

 Keyboard handling with KeyboardAvoidingView

 Success feedback with alerts

6. Filter by Course Screen
   
 Course-based filtering with Picker

 Real-time item count display

 Average price statistics per course

 Empty state handling

 Back navigation

7. Initial Menu Data
   
 20 pre-loaded menu items across all courses:

Starters (4 items): Bruschetta, Caprese Salad, Calamari Fritti, Beef Carpaccio

Main Courses (4 items): Grilled Salmon, Beef Fillet, Wild Mushroom Risotto, Herb-Roasted Chicken

Desserts (4 items): Chocolate Fondant, Crème Brûlée, Tiramisu, Cheese Platter

Sides (4 items): Truffle Parmesan Fries, Sautéed Seasonal Greens, Truffle Mac & Cheese, Creamed Spinach

Drinks (4 items): Craft Lemonade, San Pellegrino, Craft IPA, Fresh Orange Juice

8. UI/UX Enhancements
   
 Consistent color scheme and styling

 Shadow effects and elevation for cards

 Responsive button designs

 Empty state messages

 Loading states and user feedback

9. State Management
    
 React hooks for state management

 useMemo for optimized calculations

Proper state updates for CRUD operations

10. Navigation & Routing

 Type-safe navigation with TypeScript

 Proper parameter passing between screens

 Consistent header styling

Technical Features Implemented

Core Functionality

 Add new menu items

 Remove existing items

 Filter by course category

 Real-time price statistics

 Form validation

User Experience
 Responsive design

 Immediate feedback for user actions

 Intuitive navigation flow

 Error handling and validation

Data Management
 Local state management

 Efficient re-rendering with useMemo

 Proper data structure and typing

References :
Academind. 2023. React Native Tutorial for Beginners. Available at: https://www.youtube.com/watch?v=0-S5a0eXPoc [Accessed 27 September 2024].
Expo. 2024. Expo Documentation: Getting Started. Available at: https://docs.expo.dev/ [Accessed 27 September 2024].
W3Schools (no date) React tutorial. Available at: https://www.w3schools.com/REACT/DEFAULT.ASP (Accessed: 7 October 2024).
Meta Open Source (2024) React Native documentation: Tutorial. Available at: https://reactnative.dev/docs/tutorial (Accessed: 7 October 2024).
