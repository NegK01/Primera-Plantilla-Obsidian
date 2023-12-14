
---
created: <% tp.file.creation_date('DD-MM-YYYY' + ' ' + 'HH:mm') %>  
tags: DailyNote  
banner: "![[dae36a74337de05e249ce5afcec907c1.gif]]"
banner_x: 0 
banner_y: 0
---


# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, DD MMMM YYYY") %>

<< [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').subtract(1, 'd').format('YYYY-MM-DD') %>|Yesterday]] | [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').add(1, 'd').format('YYYY-MM-DD') %>|Tomorrow]] >>
> [!tip] Quote of the Day  
> > <% tp.web.daily_quote() %>

> [!todo]+ Daily Quests  
> >

> [!abstract] Notes  
>> Hi, write something right here! 