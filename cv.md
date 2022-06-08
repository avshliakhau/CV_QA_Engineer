## **CV ALIAKSANDR SHLIAKHAU**

![avatar](/imgs/avatar-22.jpg "Alex avatar")

# **[ALIAKSANDR SHLIAKHAU](https://avshliakhau.github.io/rsschool-cv/cv)** 

----------------------

## **Contacts:**
	* Addres: Belarus
	* Phone: +375 29 6907005
	* E-mail: soandr@inbox.ru 

----------------------

## **Education:**
* **The Rolling Scopes**
    	+ Front-end/ JavaScript developer (in progress)
* **Educational Center of HTP (IT-Academy)**
    	+ Functional Software Testing 
* **Belarusian State Agrarian Technical University**
    	+ Mechanical Engineer

## **Tools:**
* **GitBash/ Linux: (cd, mkdir, mv, cp,  touch, find, cat, tail, vim, grep, curl)**
* **Git/GitHub (clon, init, checkout, branch, status, add, commit,  push, pull)**  
* **DevTools (Web-testing)**
* **Postman  REST API Testing (Collections, requests, environment variables , tests, Ranner, Ranner with data)**
* **Python + PyTest+ Selenium WebDriver: tools for automation testing**

## Code examples:
```
def test_add_contact(app, json_contacts):
    contact = json_contacts
    old_contacts = app.contact.get_contact_list()
    app.contact.create_contact(contact)
    assert len(old_contacts) + 1 == app.contact.count_contact()
    new_contacts = app.contact.get_contact_list()
    old_contacts.append(contact)
    assert sorted(old_contacts, key=Contact.id_or_max) == sorted(new_contacts, key=Contact.id_or_max)
```

## Skills:
* **Russian: Native**
* **English proficiency: Pre-Intermediate in progress**

## Summary:
Responsible, inquisitive, inclined to analysis, order, self-training, with systems thinking, pedantic, analytical mindset. 