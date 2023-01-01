# Guideposts
Several new quests related to guideposts


## Quest suggestion : *What is the name of this guidepost?*
[Guideposts](https://wiki.openstreetmap.org/wiki/Tag:information%3Dguidepost) are touristic information infrastructures helping orientation. In Openstreetmap, there are described with the combination of tags `tourism=information` and `information=guidepost`. Touristic guideposts often display a location name on a small sign, which is widley tagged as `name=` in Openstreetmap. This quest aims at mapping such missing names.

### General guidelines
- ⚛️ **Atomic quests**: ☑️
- 🚧 **Established tags only**: ☑️
- 🤷 **Useful purpose**: ☑️ Guideposts have recently faced a growing interest from outdoor-related openstreetmap contributors, as they are key elements for [Node Networks](https://wiki.openstreetmap.org/wiki/Node_Networks), which are used to map bike/hiking path network, noticeably in the Netherlands and the [Alps](https://knooppuntnet.nl/en/map/hiking?position=45.18829306,5.89704611,13).
- 🕓 **Effort vs impact**: ☑️ There are around [473k guideposts](https://taginfo.openstreetmap.org/tags/information=guidepost) worlwide reported on Openstreetmap. 

### Users
- 🤔 **No unanswerable quests**: ☑️ A guidepost either has a name or not.
- 👨‍💻 **Users are no experts**: ☑️
- 🐿️ **Easy answer**: ☑️ 
- 🕵️ **Publicly accessible on foot**: ☑️ Typically located on hiking paths
- 💤 **No spam**: ☑️ Some guideposts do have a name, other don't, and the two populations are quite balanced.
- 💵 **Valuable Surveyors**: ☑️ Such data cannot be obtained from aerial views, survey is the best.

###  How to generate the quest?
The quest is generated for elements with tags `tourism=information` and `information=guidepost`, given that their is neither `name=*` nor `noname=yes`.

### User Interface 
*What is the name of this guidepost?*
The used interface will be inspired by that of the *What is the name of this place?* quest.
Ideally, a custom layout will be used (like in *What is the name of this street?* quest), to further indicate the user that the quest is about a potential name on a sign, and not about `destinations` of the guidepost. 


## Quest suggestion : *What is the elevation displayed on this guideposts?*
[Guideposts](https://wiki.openstreetmap.org/wiki/Tag:information%3Dguidepost) are touristic information infrastructures helping orientation. In Openstreetmap, there are described with the combination of tags `tourism=information` and `information=guidepost`. Guideposts located in moutainous areas often display elevation, which is widley tagged as `ele` in Openstreetmap, unit is meters. This quest aims at mapping such missing elevation indication.


### General guidelines
- ⚛️ **Atomic quests**: ☑️
- 🚧 **Established tags only**: ☑️/🔲 If `ele=` is widely used, 'no tag' is the current if such information isn't displyed, no counterpart if the information is not displayed. A Streetcomplete-inspired `ele:signed=no` tag suggested, though not widely adopted at the moment.
- 🤷 **Useful purpose**: ☑️ Guideposts have recently faced a growing interest from outdoor-related openstreetmap contributors, as they are key elements for [Node Networks](https://wiki.openstreetmap.org/wiki/Node_Networks), which are used to map bike/hiking path network, noticeably in the Netherlands and the [Alps](https://knooppuntnet.nl/en/map/hiking?position=45.18829306,5.89704611,13).
- 🕓 **Effort vs impact**: ☑️ There are around [473k guideposts](https://taginfo.openstreetmap.org/tags/information=guidepost) worlwide reported on Openstreetmap. 

### Users
- 🤔 **No unanswerable quests**: ☑️ A guidepost either has its elevation displayed or not.
- 👨‍💻 **Users are no experts**: ☑️
- 🐿️ **Easy answer**: ☑️ 
- 🕵️ **Publicly accessible on foot**: ☑️ Typically located on hiking paths
- 💤 **No spam**: ☑️/🔲  Some guideposts do have elevation displayed, other don't, and the two populations are quite balanced in mountainous area (may not be the case in other regions).
- 💵 **Valuable Surveyors**: ☑️ Such data cannot be obtained from aerial views, survey is the best.

###  How to generate the quest?
The quest is generated for elements with tags `tourism=information` and `information=guidepost`, given that their is neither `ele=*` nor `noele=yes` nor `ele:signed=no`.

### User Interface 
*What is the elevation displayed on this guideposts*
The used interface will be inspired by that of the *What is the name of this place?* quest:

The user is displayed with a box letting them write the elevation elevation, in **meters** (this quest would be disabled by default in countries using imperial units for elevation). The user input should be checked to be an integer value, and tag `ele=` created accordingly. Ideally, a custom layout will be used (like in *What is the name of this street?* quest), to further indicate the user that the quest is about a potential elevation displayed on a sign, and not about `destinations` of the guidepost.
*There is no elevation displayed* is a possible answer, in such case, a tag describing lack of elevation data should be added. To my knowledge, no such tag is widely adopted for such a prupose, so here are two possible candidates:
- `noele=yes`, used [68 times](https://taginfo.openstreetmap.org/keys/noele), inspired from `noname=yes`
- `ele:signed=no`, used [10 times](https://taginfo.openstreetmap.org/search?q=ele%3Asigned%3Dno), which is directly inspired by tag `name:signed=no` largely popularized by Streetcomplete. My personnal preference goes to this one which is more emphasizing on the *lack of elevation display* than a *lack of elevation*. Community input is very welcome.


## Quest Suggestion:  *What kind of activity is this guidepost about?*
[Guideposts](https://wiki.openstreetmap.org/wiki/Tag:information%3Dguidepost) are touristic information infrastructures helping orientation. In Openstreetmap, there are described with the combination of tags `tourism=information` and `information=guidepost`. Such guideposts can be taged to describe the kind of activities they refer to, with the following tags : `hiking`,`bicycle`, `mtb` (moutain biking), `horse`, `ski`.


### General guidelines
- ⚛️ **Atomic quests**: ☑️
- 🚧 **Established tags only**: ☑️
- 🤷 **Useful purpose**: ☑️ Guideposts have recently faced a growing interest from outdoor-related openstreetmap contributors, as they are key elements for [Node Networks](https://wiki.openstreetmap.org/wiki/Node_Networks), which are used to map bike/hiking path network, noticeably in the Netherlands and the [Alps](https://knooppuntnet.nl/en/map/hiking?position=45.18829306,5.89704611,13). Tagging missing activity on isolated guideposts will help their integration in node networks.
- 🕓 **Effort vs impact**: ☑️ There are around [473k guideposts](https://taginfo.openstreetmap.org/tags/information=guidepost) worlwide reported on Openstreetmap. 

### Users
- 🤔 **No unanswerable quests**: ☑️
- 👨‍💻 **Users are no experts**: ☑️
- 🐿️ **Easy answer**: ☑️ 
- 🕵️ **Publicly accessible on foot**: ☑️ Typically located on hiking paths (or bike, ..., which are accessible)
- 💤 **No spam**: ☑️/🔲  Depending on the area, such guidepost refer to either one of several of these activities.
- 💵 **Valuable Surveyors**: ☑️ Such data cannot be obtained from aerial views, survey is the best.

###  How to generate the quest?
The quest is generated for elements where none of the following tags are present : hiking `tourism=information` and `information=guidepost`, given that none of the following tags is attached: `hiking`,`bicycle`, `mtb`, `horse`, `ski`.


### User Interface 
*What kind of activity is this guidepost about?*
The user interface is inspired by this of the *What sport is played here?* quest, with multiple choices, each of which suggested by an image.
Answer are *hiking*, *bicycle*, *montain biking*, *horse*, *ski*. The user can also answer *None of these*. 
 
 - Option 1: Only for the activities selected, the tag `*activity*=yes` is added. If *None of these* is selected, only `hiking=no` (I chose this tag is the the most common one, and only one is needed to avoid the quest to be asked again and again).
 - Option 2:  Alternatively, each of these tags could be completed with yes|no accordingly to what the user answer. Though we will surely have plenty of `ski=no` everywhere around the globe.
 - Alternatively, the quest could be split into multiple quests alike *Is this guidepost displays hiking information* (though it could be unpleasant to systematically answer if all quests are activated by default)
 
 

