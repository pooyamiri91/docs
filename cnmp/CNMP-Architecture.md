# Communication & Notification Management Platform (CNMP)

```mermaid
graph TD;
    A[User Interface]-->B[Communication Channels];
    B-->C[Messaging Service];
    C-->D[Notification Service];
    D-->E[Analytics and Reporting];

```
```mermaid



pie title Pets adopted by volunteers
"Dogs" : 386
"Cats" : 85
"Rats" : 15

```
```mermaid




graph LR;
    A[Management Plane] -->|Configures and Monitors| B[Gateway Plane];
    B -->|Routes Requests and Data| C[Data Plane];
    C -->|Processes Data and Sends Notifications| D[User Plane];


```
