# Instagram Clone Database Analysis - SQL Queries

## Overview
This repository contains a set of SQL queries that analyze an Instagram clone database (`ig_clone`). The queries provide insights into user behavior, content trends, and potential fake accounts on the platform.

## Query Descriptions

### 1. Oldest Users
**File**: `Sql Query.sql`  
**Description**: Identifies the 5 oldest users on the platform based on their account creation date.  
**Usage**: Helps understand the platform's early adopters.

### 2. Inactive Users
**File**: `Sql Query.sql`  
**Description**: Finds users who have never posted a single photo.  
**Usage**: Useful for identifying inactive accounts that might need re-engagement campaigns.

### 3. Contest Winner Identification
**File**: `Sql Query.sql`  
**Description**: Determines the winner of a photo contest by finding the photo with the most likes.  
**Usage**: Automates contest winner selection process.

### 4. Popular Hashtags
**File**: `Sql Query.sql`  
**Description**: Identifies the top 5 most commonly used hashtags.  
**Usage**: Helps content creators understand trending topics and platform administrators identify popular categories.

### 5. User Registration Patterns
**File**: `Sql Query.sql`  
**Description**: Analyzes which day of the week most users register on.  
**Usage**: Provides insights for scheduling ad campaigns to maximize user acquisition.

### 6. User Posting Frequency
**File**: `Sql Query.sql`  
**Description**: Calculates the average number of posts per user and the total photo-to-user ratio.  
**Usage**: Measures overall user engagement and content creation patterns.

### 7. Bot Detection
**File**: `Sql Query.sql`  
**Description**: Identifies potential bot accounts that have liked every single photo on the platform.  
**Usage**: Helps maintain platform integrity by detecting suspicious activity.

## Database Schema
The queries assume the following tables exist in the `ig_clone` database:
- `users`: Contains user account information
- `photos`: Stores photo posts
- `likes`: Tracks photo likes
- `tags` and `photo_tags`: Manage hashtag functionality

## How to Use
1. Ensure you have the `ig_clone` database set up with appropriate tables and data
2. Run the queries individually in your MySQL client to get the specific insights
3. Modify the queries as needed for your specific database structure

## Contribution
Feel free to fork this repository and submit pull requests with additional analytical queries or improvements to existing ones.

## License
This project is open-source and available under the MIT License.
