# All Get API document for B.E.

---

---
### UserData 
  - URL:

> [!WARNING]  
> Need B.E.

  - Body:
>string Email
> 
>string Password
  - Return: 
> [UserData](../JsonFormat/UserData.json) `Click to view`

---
### Boss Data
- URL:

> [!WARNING]  
> Need B.E.

- Body:
>
- Return:
> [BossData](../JsonFormat/GetBossData.json) `Click to view`

---
### Get Boss fight Leaderboard
- URL:

> [!WARNING]  
> Need B.E.

- Body:
> string UserId `To get current user rank even if user not in top of leaderboard`
- Return:
> [Boss Leaderboard](../JsonFormat/BossLeaderBoard.json) `Click to view`

---
### Get PvP Teams
- URL:

> [!WARNING]  
> Need B.E.

- Body:
> int userElo `To get sum user with near elo to current user`
> 
> int amount `Amount of random user with match elo condition to return (Ex: if amount == 3 => expect return 3 user)`
- Return:
> [Defense teams](../JsonFormat/DefenseTeams.json) `Click to view`