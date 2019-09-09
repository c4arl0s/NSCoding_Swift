# NSCoding_Swift

NSCoding_Swift

# NSCoding

NSCoding_ObjectiveC

- A protocol that enables an object to be encoded and decoded for achiving and distribution.

# There are many ways to Save data to disk in iOS

- Raw file APIS
- Property List Serialization
- Core data
- Third party solutions like Realm.
- .. and of course NSCoding.

You can convert any object to NSData with the NSCoding protocol.

# There are two approaches to persist an instance of a class.

| Local File System   |      NSUserDefaults      |  
|---------------------|:------------------------:|
    

# Using Local File System

# Steps to persist in Local File System

- write your class
- Implemente protocol NSCoding
- Conform protocol in implementation file.
- Archive
- Create the paths in the file system
- Unarchive to test if you saved correctly.
