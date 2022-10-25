---

creation date: <% tp.file.creation_date() %>
tabs: Log <% tp.file.title.split('-')[0]%>

---

# <% tp.file.title %>

## Daily Check List

### Start of Day

- [ ] Check Email

- [ ] Check Teams

- [ ] Check Calendar


### End of Day

- [ ] Show Offline

- [ ] Clean Unused Headings in Daily Log

- [ ] Check tomorrow's Calendar

- [ ] Daily Status Update

- [ ] ADO daily items

## Tasks

#### Over Due

```tasks
not done
due before <%tp.date.now("YYYY-MM-DD")%>
```

#### Due Today
```tasks
not done
due on <%tp.date.now("YYYY-MM-DD")%>
```
#### New Today


## Meeting Log

### 

## Daily Log

### 

## Notes for night call



#### Tasks without timeframe

```tasks
not done
no due date
```

#### Done Today
```tasks
done one <%tp.date.now("YYYY-MM-DD")%>
```
