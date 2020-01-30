<img src="https://staging.tiger.sohotokenlabs.com/img/ftl-bugcatcher.png" alt="Faster Than Light BugCatcher" title="Faster Than Light BugCatcher" width="300" />

# BugCatcher Test Results


**Project Name**: `faster-than-light_bandit-random_module_master`

**Test ID**: `uEF3nAhvVjH3pLY9nVLdcFH0yVoQdNBWg0SkBEeC`

**GitHub Tree SHA**: `ddcbfa156204828a5ac164aa2b344b4d218cb04d`

#### Languages found: 
`python`

#### Testing Tools Used: 
`bandit`

#### Files Tested: 
```
bandit-random_module.py
```

## RESULTS:
- (LOW) `blacklist` Standard pseudo-random generators are not suitable for security/cryptographic purposes. 
	- bandit-random_module.py (lines 10 - 10) 
	- bandit-random_module.py (lines 5 - 5) 
	- bandit-random_module.py (lines 6 - 6) 
	- bandit-random_module.py (lines 7 - 7) 
	- bandit-random_module.py (lines 8 - 8) 
	- bandit-random_module.py (lines 9 - 9) 
##

<img src="https://staging.tiger.sohotokenlabs.com/img/bugcatcher-approved.png" alt="Faster Than Light BugCatcher" title="Faster Than Light BugCatcher" width="300" />
