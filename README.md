## Project files

`weatherfiles.zip` contains all the weatherman files. You will need to extract that to see all the CSV files.

Read the followings Tasks and Guidelines carefully to learn more about the project.

## Tasks

When making the submissions, your repo's directory layout should be in this way:

- weatherfiles
- utils
- tasks
    - t1.py
    - t2.py
    - t3.py
    - t4.py

Make sure to upload your solution to a GitHub repo (either have it public, or share it with your teamlead's username).

**Note:** Your submissions should be a pull request with appropriate branch and pull request name.


### Guidlines

- There should be a file in your project, which only reads the file.
- You should import and use that reading function or class everywhere else.
- Your task files (t1.py, t2.py etc.) should not have the reading logic. It should only have the logic which the task
  requires.
- Each task must have its separate file, and named as per its number (t3.py will only contain solution for task3)
- You must have reviewed your PR yourself before sending me for the review.
- Once you have done any task, and its PR is approved, merge that PR and start your work in another branch and create separate PR for it.
- Before doing the next tasks, ensure you have completed and merged the previous tasks
- You cannot use any third party libraries. Just use built-in libraries Python comes with by default
  

### Tasks

1. Find the year and temperature values for the minimum temperature. e.g. 2011 => -20
2. Find the year and temperature values for the maximum temperature. e.g. 2004 => 45
3. Find all the dates in which Max TemperatureC and Min TemperatureC has a difference of exactly 7.
4. Find all the unique events present in the files. (Events is the 2nd last column in files.)
5. Find all the months in which the event "Rain" occurred. (if the date is 2016-3-7, the month will be 3.)

