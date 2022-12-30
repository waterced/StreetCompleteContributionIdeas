# Guideposts
Several new quests related to guideposts

## Guidelines

### General guidelines
- ⚛️ **Atomic quests**: ☑️
- 🚧 **Established tags only**: ☑️
- 🤷 **Useful purpose**: ☑️ [Guideposts](https://wiki.openstreetmap.org/wiki/Tag:information%3Dguidepost) are touristic information infrastructure helping orientation. There use in . In Openstreetmap, there are described with the combination of tags `tourism=information` and `information=guidepost`. Signposts have recently faced a growing interest from outdoor-related openstreetmap contributors, as they are key elements for [Node Networks](https://wiki.openstreetmap.org/wiki/Node_Networks), which are used to map hiking path network, notably in [French Alps](https://knooppuntnet.nl/en/map/hiking?position=45.18829306,5.89704611,13).
- 🕓 **Effort vs impact**: ☑️ There are around [473k guidepost](https://taginfo.openstreetmap.org/tags/information=guidepost) worlwide reported on Openstreetmap. 

### Users
- 🤔 **No unanswerable quests**: ☑️ There is either a name or no.
- 👨‍💻 **Users are no experts**: ☑️
- 🐿️ **Easy answer**: ☑️ 
- 🕵️ **Publicly accessible on foot**: ☑️ Hiking routes
- 💤 **No spam**: ☑️ Some guidepost do have a name, other don't.
- 💵 **Valuable Surveyors**: ☑️ Such data cannot be obtained from aerial views, survey is the best.




## Name
### General guidelines
- ⚛️ **Atomic quests**: ☑️
- 🚧 **Established tags only**: ☑️
- 🤷 **Useful purpose**: ☑️ [Guideposts](https://wiki.openstreetmap.org/wiki/Tag:information%3Dguidepost) are touristic information infrastructure helping orientation. There use in . In Openstreetmap, there are described with the combination of tags `tourism=information` and `information=guidepost`. Signposts have recently faced a growing interest from outdoor-related openstreetmap contributors, as they are key elements for [Node Networks](https://wiki.openstreetmap.org/wiki/Node_Networks), which are used to map hiking path network, notably in [French Alps](https://knooppuntnet.nl/en/map/hiking?position=45.18829306,5.89704611,13).
- 🕓 **Effort vs impact**: ☑️ There are around [473k guidepost](https://taginfo.openstreetmap.org/tags/information=guidepost) worlwide reported on Openstreetmap. 

### Users
- 🤔 **No unanswerable quests**: ☑️ There is either a name or no.
- 👨‍💻 **Users are no experts**: ☑️
- 🐿️ **Easy answer**: ☑️ 
- 🕵️ **Publicly accessible on foot**: ☑️ Hiking routes
- 💤 **No spam**: ☑️ Some guidepost do have a name, other don't.
- 💵 **Valuable Surveyors**: ☑️ Such data cannot be obtained from aerial views, survey is the best.

###  Quest generation
Generated for elements 
### User Interface 
*Does this guideposts has a name* (y/n)
If yes, creates tag `name=`, if not add the tag `noname=yes`

## Elevation
Guideposts located in moutain areas often display elevation, which is widley tagged as `ele` in Openstreetmap, unit is meters.

*Is the elevation displayed on this guideposts* (y/n)
If yes, elevation should be asked, in **meters** (this quest would be disabled by default in countries using imperial units for elevation) and tag `ele=` created accordingly. 
If no, a tag describing lack of elevation data should be added. To my knowledge, no such tag is widely adopted for such a prupose, so here are two possible candidates:
- `noele=yes`, used [68 times](https://taginfo.openstreetmap.org/keys/noele), inspired from `noname=yes`
- `ele:signed=no`, used [10 times](https://taginfo.openstreetmap.org/search?q=ele%3Asigned%3Dno), which is directly inspired by tag `name:signed=no` largely popularized by Streetcomplete. My personnal preference goes to this one which is more emphising on the *lack of elevation display* than a *lack of elevation*. Community input is very welcome.
- 
### Activities related to the route
Such guidposts are mostly associated
Activated to for when none of the following tags is attached: hiking, bicycle, mtb, horse, ski.
*What kind of route is this guidepost describing?*
 hiking, bicycle, montain biking, horse, ski, None of these actvities
 `hiking=yes`,`bicycle=yes`, `mtb=yes`, `horse=yes`, `ski=yes`.
 Each of these tags will be completed with yes|no accordingly to what the user answer.



``
