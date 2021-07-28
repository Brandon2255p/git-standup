# CLI
## Repo Management

Add a new repo
```
standup doc add [NAME] [GIT URL]
```
Remove a repo
```
standup doc remove [NAME]
```
Select a repo
```
standup doc select
```

## User Management

Add a user
```
standup user add [NAME] [GIT USER]
```
Remove a user
```
standup user remove [NAME]
```

## Standup

Do a standup entry for the day

```
standup today
```

View previous standup

```
standup view last
```

# Standup Repo Setup

## Structure

```
| users.md
| config.md
| docs
|  | 2021-07
|  |  | 2021-07-25 Monday.md
|  |  | 2021-07-26 Tuesday.md
```