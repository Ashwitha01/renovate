file for which I planned to apply renovate is : test-renovate/versions.gradle
a veryy sample code I have added, just to explain the usecase

in renovate.json I have added:
"includePaths": [
      "**/test-renovate/versions.gradle**"
    ],
to scan versions.gradle file.    

Output:
Renovate is not scanning the repo.

Expecting Output:

test-renovate/versions.gradle is my gradle file.
I want renovate scan only this file and raise PR and ignore rest of the file.
