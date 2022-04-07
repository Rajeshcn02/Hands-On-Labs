</details>

<details>
   <summary> <strong> Task 1:  </strong> </summary>
  
 # Create a Branch Protection Rule 
  
So Protecting branches are like we say it is a policy or security feature which you can enable in your branches . So that you can protect the changes which was going to your main branch.

In your GitHub repository go to the settings tab and click the branches option as shown here:
  
 ![branch protection rule](https://user-images.githubusercontent.com/97287103/162140939-9d10e7d0-4f38-4145-9b52-e635a34d92f8.png)

  Now add a new rule and define which branch you want to protect. e.g. provide the pattern name `main` or `master`.
  
 Next you select the following options:
  
1. `Require pull request reviews before merging`
2. `Include administrators`
  
 ![pattern matching](https://user-images.githubusercontent.com/97287103/162141802-70736c68-1ee0-412b-9f08-a99e1c66e735.png)
  
 ![2022-04-07 12_52_39-Window](https://user-images.githubusercontent.com/97287103/162143149-4517e0ce-fc5d-412d-933f-2646cdee6344.png)

 Now save this Branch Rule and see How it Works.
  
 To check whether its working or not , create a change one of the files in the `main` or `master`  branch. 
  
  ![cant commit on master](https://user-images.githubusercontent.com/97287103/162144769-59d3df6d-0dbe-47cc-bf87-ac6c389c333d.png)
  
   You can’t commit to `main` or `master` branch   because it is a protected branch.Now you will create a new branch for this commit and start a pull request. 
 
