---
createdAt: 2024-03-07T12:08Z
modified: 2024-03-11T10:01Z
---
This is repo serves as a template for taking notes about life in a (hopefully) organized manner. It's basically a digital journal with a separate section for organizing job/apartment-hunting efforts. I currently use this file structure within [Obsidian](https://obsidian.md/) to better organize myself.

## File structure

Below is a breakdown of the file structure. **NOTE:** In this description, the root folder's contents are sorted alphabetically while other content is not. I thought it would be easier on the brain to list nested files first to reduce the visual jumping back and forth.

```
/'Apartment Hunting'                                    #
    /2024                                               # The year you're looking for an apartment in
        /Active                                         # See below
        /Inactive                                       # See below
/Career                                                 #
    /'Skill Development'.md                             # Jot down skills you want to improve on or learn
    /People                                             # This is for a mix of networking and linking multiple role opportunities to the same person
    /'Job Hunting'                                      #
        /'Questions to ask during the interview'.md     # A growing collection of questions
        /'Interview Practice'                           #
            /'Technical Ideas'.md                       # Practice problems and/or projects
        /2024                                           # The year you're looking for a job in
            /'Salary and Finances'.md                   # A space to map out your current financial situation and brain dump salary
            /Leads                                      # Aka prospective companies you may want to work for
                /Active                                 # See below
                /Inactive                               # See below
                /Misc.md                                # Essentially a scratch pad for notes to be sorted later
/DailyNotes                                             # Journal
/Ideas                                                  #
/Templates                                              #
```

I like having `Active` and `Inactive` directories as a way to see what's still available or interesting from a high level view. Feel free to change it however you like.

## File metadata

Most files have a YAML metadata section at the top that looks like this:

```
---
createdAt: YYYY-MM-DDTHH:mmZ (ISO 8601, ex: 2024-03-11T09:53Z)
modifiedAt: {same type as createdAt}
tags:
- tag1
- tag2
---
```

The `tags` field kind of mirrors the directory structure. I did this in case I want to switch the directory structure but still have some way to link things together.
