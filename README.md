# grand2

-This application is a insurance companies and it's own doctors.
-When you select a insurance company its open in another activity the doctors that contracted with this company
-We will find the slider that contains the doctor ( selected doctor based on the slider showing doctor)
-We can send direct message to the docotr
-We can open the chat between me and the doctor ( that chat contain the messages that the used have been sent )
  - The application support working offline because the data is local in Sqlite.
  - Application working with Mvvm design pattern.
  - Easy to use
  - Easy to Develope
  - Easy to understand
  - Easy for testing
  
  
 1- The application contains 3 Tables in Database.
      - InsuranceTable
      - DoctorTable (contains the foreign key of the insurance id)
      - MessageTable (contains the foreign key of the doctor id)
  
 2- The DAO class contains the hole queries.
 3- Each Table have his own EntryModel.
 4- Each EntryModel have his own Repository Class that contains the business logic.
 5- Each Repository Class contains his own ViewModel.
 6- UI just calls the ViewModels Classes only.
