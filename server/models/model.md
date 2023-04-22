# DataModel

```txt
User
  _id           String
  firstName     String
  lastName      String
  friends       Array<Object>
  email         String
  password      String
  picturePath   String Ref
  location      String
  occupation    String
  viewedProfile Number
  impressions   Number

Post
  _id           String
  userId        String Ref
  firstName     String
  lastName      String
  location      String
  description   String
  userPicturePath String Ref
  picturePath   String Ref
  likes         Object<String Ref>
  comments      Array<String>

Friend (Sub Doc)
  _id           String
  firstName     String
  lastName      String
  picturePath   String Ref
  occupation    String
  location      String

Images
  path

```
