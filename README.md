# AB4Py-
AB4Py python 3 module for working with MacOS/OS X Address Book

Needed the Python to Objective-C bridge library
Actual version PyObjC 5.1.2 was released on 2018-12-13
https://pyobjc.readthedocs.io/en/latest/index.html#

Function in this module:
SearchPersonByName(Addr_book, Name)\n 
GetFullNamePerson(RefPerson)\n
GetJobDataPerson(RefPerson)\n
GetPhonesPerson(RefPerson)\n
GetEmailsPerson(RefPerson)\n
GetAddressesPerson(RefPerson)\n
\n
SetNewPersonRecord(LastName, FirstName='', MiddleName='')\n
SetJobName(RefPerson, Organization, JobTitle ='', Department='')\n
FormingPersonalRecord(record_ar, Organization = '')\n

print_person_date(RefPerson)\n
rus_phone_numb_norm(ph_numb)\n
