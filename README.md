# AB4Py-
AB4Py module or working with MacOS/OS X Address Book

Needed the Python to Objective-C bridge library
Actual version PyObjC 5.1.2 was released on 2018-12-13
https://pyobjc.readthedocs.io/en/latest/index.html#

Function in this module:
SearchPersonByName(Addr_book, Name,)
GetFullNamePerson(RefPerson)
GetJobDataPerson(RefPerson)
GetPhonesPerson(RefPerson)
GetEmailsPerson(RefPerson)
GetAddressesPerson(RefPerson)

SetNewPersonRecord(LastName, FirstName='', MiddleName='')
SetJobName(RefPerson, Organization, JobTitle ='', Department='')
FormingPersonalRecord(record_ar, Organization = '')

print_person_date(RefPerson)
rus_phone_numb_norm(ph_numb)
