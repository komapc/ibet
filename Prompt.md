Prompt:
Project Title: News Scoop Prediction Market App

Adjusted Project Goal: To develop a visually engaging and intuitive platform where users can bet virtual tokens on news events, with seamless navigation and interactive elements.

I. Core Features (Revised):

Prediction Feed (Home Screen):

UI Elements (as per the image with enhancements): App Header: "News Scoop" logo and title ("Prediction Market" subtitle). Quick Stats Summary (Top of Feed): Interactive Bet Summaries: Instead of just numbers, display the actual bets that fall into each category. Make these summaries clickable, leading to a filtered view of the Bet Feed showing only those bets. Active Bets (3): A visually distinct box showing the number of active bets. Clicking this box filters the feed to show only active bets. Closing Soon (0): A visually distinct box showing the number of bets closing soon. Clicking this box filters the feed to show only bets closing soon. Resolved (0): A visually distinct box showing the number of resolved bets. Clicking this box filters the feed to show only resolved bets. Use the icons from the image for visual clarity (arrow for Active, clock for Closing Soon, checkmark for Resolved). Filter Bets (Below Quick Stats): Replicate the buttons from the image: "Active (3)", "Closing Soon (0)", "Resolved (0)". These should function identically to the interactive summaries above, filtering the Bet Feed. Use the same icons. Bet List (Below Filters): The actual list of active bets, following the description from the previous instruction set (Bet Question, Deadline, Upvote/Downvote, User Participation, Source Information). If no active bets are available, display the "No bets found" message with the "+ Create the First Bet" button (as shown in the image).

Create Bet Button: (Top right corner, as per the image). Opens the Bet Creation screen. Functionality: The primary screen for browsing and interacting with bets. Clear visual hierarchy and intuitive filtering. AI-Assisted Bet Creation:
Functionality: (No change from previous instruction set). User Profile:

UI Elements (as per the image with clarification): User Information: Profile Image, Nickname ("Marik marik"), Joined Date ("Joined 8/17/2025"). Token Balance: "100 Tokens" (with a token icon). Accuracy: "0% Accuracy". Quick Stats: "Bets Created (1)", "Participated (0)", "Total Winnings (+0)". Navigation links (see below). Functionality: (No change from previous instruction set). Bet Resolution (Administrator Only):

Functionality: (No change from previous instruction set). Hall of Fame (Leaderboard):

Functionality: (No change from previous instruction set). Authentication:

Google Login integration. II. Navigation (NEW - Swipable):

Implement a bottom navigation bar or a swipable view to allow users to easily switch between the main sections of the app: Feed (Home): The primary Bet Feed screen. (As per the image). Create Bet: The AI-assisted bet creation screen. Leaderboard: The Hall of Fame. Profile: The User Profile screen. Use clear icons for each section in the navigation bar (or swipable indicator). III. Database Schema:

(No changes from previous detailed schema).

IV. AI Prompt for Bet Question Generation:

(No changes from previous AI prompt).

V. Technology Stack (Suggested):

(No changes from previous suggested technology stack).

VI. Development Process (Revised):

Phase 1: Core Functionality & Navigation (MVP): Implement the Bet Feed (with interactive summaries and filters), User Profile, Authentication, Bet Placement, and swipable navigation. Focus on a visually appealing and intuitive UI based on the provided image. Implement the Administrator Resolution Screen (with manual payout calculation initially). Get the AI prompt working and integrated. Phase 2: Automation & Refinement: Automate the payout calculation and distribution process. Implement the Hall of Fame leaderboard. Add user moderation features. Phase 3: Social Features & Enhancements: Implement Following/Followers functionality. Add social sharing features. Implement more advanced Badges. Refine the AI prompt and improve its accuracy. VII. Deployment, VIII. Testing, IX. Important Considerations:

(No changes from previous instruction set).

Key Improvements in This Version:

Visual Fidelity: The instructions now explicitly reference the provided image, ensuring the app's design closely matches the intended look and feel. Interactive Summaries: The "Active Bets", "Closing Soon", and "Resolved" summaries are now interactive, providing a more engaging user experience. Swipable Navigation: The addition of swipable navigation makes the app more user-friendly and intuitive. Prioritized Development: The development process is now structured to focus on the most critical features first, ensuring a successful MVP.

Prompt2:
Instruction: Refactor News Scoop App - Betting, Tokens, Navigation

Priority: CRITICAL

Context: The current News Scoop app exhibits usability and functional shortcomings that degrade the user experience. The following instructions detail the required improvements; the implementation approach is left to Base44's optimization algorithms.

I. Enhance the Betting Card Component (BetCard): User Interaction & Visuals

Goal: Streamline betting, enable variable token bets, adopt a modern aesthetic.

Functional Requirements:

Simplified Voting Process: The user should be able to initiate the betting process with a single, clear action (e.g., tapping a "Bet" button or area on the card). Dynamic Token Input: Following the initial betting action, the user should be presented with a means to specify the exact number of tokens they wish to wager. This could be an inline input field or a modal dialog, optimized for mobile input. Balance Awareness: The user's current token balance must be conspicuously displayed near the token input, updating in real-time as they enter their bet amount. Balance Enforcement: The system must prevent the user from wagering more tokens than they possess. Implement clear and immediate visual feedback if the user attempts to exceed their balance (e.g., a red error message, disabled bet confirmation). Visual Requirements:

Modern Design Language: The overall design of the betting card should be contemporary and visually appealing. Employ clean lines, a restrained color palette, and ample whitespace. Clear Hierarchy: The bet question, deadline, potential payout, and betting controls should be arranged in a logical and visually distinct manner. Visual Examples: [Base44: Consult design resources such as Dribbble, Behance, or UI pattern libraries for contemporary betting interface examples. Adapt and integrate those visual principles into the BetCard component.] II. Rectify Token System Irregularities: Stable & Accurate Balances

Problem: Users are experiencing unintended token increases upon page refreshes, disrupting the platform's virtual economy. Objective: Establish a robust token management system that ensures balances are persistent, accurate, and immune to unintended manipulation. Constraints: Balance Persistence: Token balances must be reliably stored and retrieved across sessions. Transaction Integrity: Token modifications (bet placement, bet resolution) must be atomic and consistent. Unauthorized Modification Prevention: No mechanism (intentional or accidental) should allow users to artificially inflate their token holdings. Success Metrics: Token balances remain consistent across page refreshes, logouts, and device changes. Token transactions accurately reflect bet placements and resolutions. III. Transform Navigation: Seamless Transitions Between Sections

Goal: Implement smooth, client-side navigation between the Feed, Create Bet, Leaderboard, and Profile sections, eliminating disruptive page reloads. Requirements: Client-Side Routing: Employ a routing solution that allows navigation without full-page refreshes. Visual Feedback: Provide clear visual cues to the user during navigation transitions (e.g., subtle animations, loading indicators). Performance Optimization: Ensure that navigation is fast and responsive, minimizing perceived latency. Exclusions: Avoid complete page reloads during navigation between the core sections of the app. Minimize data transfer during navigation; load only the necessary resources for each view. IV. Elevate Overall User Experience: Fluidity & Responsiveness

Objective: Maximize the app's perceived performance and responsiveness through intelligent optimization techniques. Strategies: Performance Profiling: Analyze the app's performance characteristics to identify bottlenecks. Resource Optimization: Compress images, minify code, and eliminate unnecessary assets. Lazy Loading: Defer loading of non-critical resources until they are needed. Code Splitting: Divide the application into smaller chunks to improve initial load time. Caching: Leverage browser caching to reduce network requests. Measurement: User-perceived loading times, frame rates, and overall responsiveness should be demonstrably improved. Success is measured by:

A betting system that is easy and pleasant to use. Accurate and persistent token balances. Fluid and seamless navigation throughout the application. An overall responsive and optimized user experience
