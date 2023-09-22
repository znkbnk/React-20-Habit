Step 1: Install Chart.js

Install the Chart.js library in your React
project using npm or yarn.

Step 2: Import Chart.js

In your App.js file, import Chart.js at the top 
of the file along with your other imports.

Step 3: Create a Chart Container

In your JSX code, create a container for your chart. 

Step 4: Create the useEffect for showChart

Inside your App component, define a useEffect block
where you create the showChart function. This
useEffect should run once when the component mounts
and update whenever completedHabitsData changes.
Use the 
https://react-chartjs-2.js.org/examples/vertical-bar-chart
code as a template example.

Step 5: Modify HabitList.js file:

In you HabitList.js file change from setCompletedHabits
to setHabits. This change impacts how habits are updated
within the handleCompleteClick function.

Step 6: Update the styles.css file

Inside the styles.css file, scroll to an appropriate 
place where you want to add the styles for .chart-container.
Create the styles for the .chart-container class. 

