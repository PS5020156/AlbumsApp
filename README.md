# AlbumsApp

Albums app Used libraries & Components

Kotlin as the main language for development of this app; 
Clean code architecture has been used with domain, data & presentation layer.
MVVM Design Pattern; 
Single Activity Architecture.
SOLID Principles has been followed.
Single source of truth.
Dagger HILT for dependency Injection; 
View model and LiveData/Flow for communication between UI Component and data layer; 
Coroutines for async operations; 
Constraint layout for layout creation; 
Retrofit2 for network requests; 
Room Library; 
DataBinding Library for binding the View; 
Navigation Architecture Component/Navigation Host, Navigation Graph, NavigationController; 
DiffUtil, ListAdapter & RecyclerView; 
Mockito Library for Testing, Kotlin coroutines test, Google truth library for assertion Junit for testing. Espresso and Barista library used for UI testing. 


Task Implemented to this project 

Task0: Create a branch and run sample default project just to ensure emulator and initial project setup is successful.

Task 1:: Inside gradle file declare all the required dependencies to be used in this Project. for instance, retrofit dependency; Livedata, lifecycle, etc.

Task 2:: Create the Project structure following Clean Code architecture & MVVM pattern.[for instance,
Domain layer; Data Layer; Presentation layer & further divide in to 
data(local/remote) - repository utility ui -viewmodel/fragment/feature -di (dagger hilt dependency injection) -base ] 

Task 3: Create required Kotlin classes(data class) which will hold the Albums list(model classes).

Task 4:: Call the Api using retrofit and see result returning successfully.(use suspend func for coroutines)

Task 5:: Create Resource Sealed class inorder to handle the Success and Failure Response.


Task 7:: inside ViewModel we need to call the api via usecase(domain layer) and handle the stuff using Livedata/Flow.

Task8:: on UI Component/Activity/Fragment We need to follow Single Activity architecture.

Task9: So far only one fragment is cretaed as per requirement using Navigation Architecture component.

Task10: Implementation of Adapter using DiffUtil/RecyclerView.

Task12: Implement dataBinding for dataflow from viewmodel to UI & vice versa.

Task13: Implementation of Dagger HILT for dependency Injection.

Task14: Implement Room Library.

Task15: Unit testing for ViewModel class.

Task16: UI testing with espresso and barista

Task17: Check the code everything is fine and do the testing on device/emulator.

Manual Testing::
1. List is populating in sorted format.
2. in case of network issue, error will get prompted.
