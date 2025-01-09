# sanfranschizo.com
You are the mayor of San Franschizo. Best of luck sucka


Here's a detailed plan for "Mayor of San Franschizo" based on the Peter Lunch's blog on planning and building a programming project:

Step 1: Define the Project
Project Definition:

    Concept: An LLM-powered city management game where you play as the mayor of a satirical San Francisco, navigating through AI-generated events with decisions affecting your popularity.
    MVP Features:
        Basic city management interface.
        LLM-generated events with multiple choice responses.
        A "Popularity" system that reacts to player decisions.
        Simple event difficulty scaling.
        Basic recall mechanism if popularity drops.
        Local leaderboard for tracking player progress.
    Nice to Haves:
        Advanced LLM interactions for more nuanced event outcomes.
        Multiple city districts with unique challenges.
        Complex recall campaign with phases and LLM-driven public opinion.
        Online integration for a global leaderboard.
    Completion Criteria: MVP complete when basic gameplay is functional, including LLM integration, popularity tracking, and recall. Full release when all "Nice to Haves" are implemented.


Step 2: Set Up Your Workflow
Tools Needed:

    Development Environment: Visual Studio Code or similar for coding; Unity or Godot for game development.
    Version Control: GitHub for managing code changes.
    Project Management: Trello or Jira for task tracking.


Workflow Setup:

    Initiate a Trello board with columns like "To Do", "In Progress", "Testing", "Done".
    Create cards for each feature (e.g., "LLM Event Generator", "Popularity Score System").


Step 3: Break Down the Project
Components to Build:

    Game Engine & UI:
        Design a simple, engaging UI for managing the city, viewing popularity, and making decisions.
    LLM Integration:
        Event Generator: Use LLM to create unique events. API integration with an LLM service.
        Decision Options: LLM provides at least three options for each event, with outcomes reflecting current city state.
    Popularity Mechanics:
        Score System: Popularity score updates based on event outcomes, with LLM determining the impact.
        Visual Representation: A meter or percentage display for the player's popularity.
    Event Difficulty Scaling:
        Algorithm: Over time, increase event complexity or reduce the attractiveness of response options.
    Recall Campaign:
        Trigger: Popularity below 30% for three in-game days initiates a recall campaign.
        Process: LLM narrates the campaign's progress, public sentiment, and final vote.
    Leaderboard:
        Backend: Store player stats (time, popularity, events managed).
        Frontend: Display leaderboard within the game or via a web interface.


Tasks:

    Backend Development:
        Set up server for LLM requests, database for game state and leaderboard.
        Implement scoring and recall logic.
    Frontend Development:
        Design and code the game interface.
        Integrate LLM responses into the UI for event handling.
    LLM Integration:
        Write functions to query LLM for event generation and outcome prediction.


Step 4: Build and Iterate
Action Plan:

    Week 1-4:
        Set up game engine, basic UI, and LLM integration for event generation.
        Implement initial popularity tracking.
    Week 5-8:
        Develop the event response system, including option generation by LLM.
        Begin event difficulty scaling and basic recall mechanics.
    Week 9-12:
        Refine the popularity system, making it more responsive to player decisions.
        Implement and test the recall campaign.
        Set up local leaderboard.


Iteration:

    Playtesting: Regular sessions to adjust event balance, popularity impact, and recall frequency.
    Feedback: Collect and integrate player feedback to tweak game mechanics.


Step 5: Release and Update
Release Strategy:

    MVP Release: Launch with basic features on platforms like itch.io or Steam.
    Marketing: Focus on the novelty of LLM-driven gameplay, share gameplay clips, and promote the leaderboard.


Post-Release:

    Updates: 
        Enhance LLM interaction for richer events and outcomes.
        Add more districts and types of events.
        Implement online leaderboard for broader competition.
    Community Engagement: 
        Use social media to share top leaderboard scores or notable in-game events.
        Encourage community feedback for new LLM-generated content or gameplay mechanics.


By following this plan, "Mayor of San Franschizo" will not only leverage the latest in LLM technology for a unique gaming experience but also incorporate addictive game mechanics like popularity-based progression and competitive elements through the leaderboard, aiming for both virality and player retention.
