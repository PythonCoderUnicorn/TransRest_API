# TransRest_API 🏳️‍⚧️

A repo for Transgender Affirmations. 

> Note: This API is running on a **FREE plan** which is 500 hours per month of active run time. If and when the run time is >500 hours it shuts down and needs to be restarted the following month. So if this API is not working, then this is why. 

## Genesis 🏳️‍⚧️

The idea is a combination of a conversation about Transgender people needing to take a break and rest. 
The word association of rest is Restful API,
then Trans + Rest + API became TransRest_API.


## Data 🏳️‍⚧️

The data is positive affirmations and neutral sayings regarding 
being Transgender. All affirmations are gender neutral so _everyone_
is included. The affirmations data is mostly in English, 
but you can help it have more than English.

## Data Guideline 🏳️‍⚧️

Adding to the json file includes 

- affirmations that are gender neutral
- affirmations that can apply to most people on their Transgender journey

### Adding Persons 🏳️‍⚧️

This data has famous Transgender people, the affirmations have everyone as living and
uses the question of _"if you could have lunch with any famous person, 
who would you have lunch with?"_ as basis for affirmations involving the end user. 
The end user needs to be part of the narrative with famous person in some relation 
to their profession. 

- any Transgender person who is publically known, has stated pronouns, their profession/ what they do and some fiction about how they will interact with the end user. 
- `profession` + `pronouns` + `fiction`

```
"Actress Laverne Cox (she/her) has a TV scene that mentions your blog"
```

### Adding Characters 🏳️‍⚧️

You can add Transgender or GNC characters from TV shows/ films. 
Characters not formally Transgender but are considered Trans are 
accepted, example Star Trek Jadzia Dax. All characters needs to have the TV/film where the character is from. 

This section can have:

- basic info on the character
- fiction that includes the end user
- what this character does
- any superpowers this character has

- `(origin)` + `name` + `pronouns` + `option`

```
Star Trek Jadzia Dax (she/her) is a Trill species, which embodies other genders
```

### Adding Exoplanets 🏳️‍⚧️

A section of this data are names of [NASA Exoplanets](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PSCompPars) in
the attempts to add to positive Sci-Fi thinking and affirmations. 
This is one part truth (exoplanet) and one part fiction or affirmation that 
is overall positive.

- `Exoplanet name` + `fiction`
- `Exoplanet name` + `affirmation`

Fiction
```
Planet CD Cet b (CD Cet) is known for their Transgender services
```

Affirmation
```
You must come from the EPIC planets, EPIC 206024342 b, c and d
```



