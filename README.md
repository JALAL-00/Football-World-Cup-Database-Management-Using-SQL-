FIFA Football World Cup Management System

This project is a Database Management System (DBMS) implementation for managing FIFA Football World Cup data. It includes comprehensive information about teams, players, matches, referees, and stadiums. The system tracks team performance, match outcomes, and individual player statistics, among other essential details.

Key Components

Teams

	•	Attributes:
	•	ID
	•	Name
	•	Rank
	•	Team Stats:
	•	Matches Played
	•	Wins
	•	Losses
	•	Draws

Matches

	•	Attributes:
	•	ID
	•	Team1 (ID)
	•	Team2 (ID)
	•	Winner (Team ID)
	•	Loser (Team ID)
	•	Date
	•	Stadium ID
	•	Referee ID

Stadiums

	•	Attributes:
	•	ID
	•	Name
	•	Location
	•	Total Matches
	•	Capacity

Referees

	•	Attributes:
	•	ID
	•	Name
	•	Age
	•	Matches (Officiated)
	•	Country

Coaches

	•	Attributes:
	•	ID
	•	Team ID
	•	Name

Players

	•	Attributes:
	•	ID
	•	Name
	•	Team ID
	•	Age
	•	Jersey Number
	•	Captains:
	•	ID
	•	Team ID
	•	Years of Captaincy

Player Stats

	•	Attributes:
	•	ID
	•	Team ID
	•	Goals
	•	Assists
	•	Matches Played
	•	Fouls

Player Specialities

	•	Attributes:
	•	ID
	•	Position
	•	Skill

This project showcases the application of a relational database to manage and query FIFA World Cup data effectively.
