
# Activity List and Dependencies

| Activity ID | Activity Name | Duration (days) | Predecessor(s) |
|-------------|---------------|-----------------|----------------|
| A1.1 | Clarify project goals | 8 | --- |
| A2.1 | Data Collection | 7 | A1.1 |
| A2.2 | Clean and prepare dataset | 4 | A2.1 |
| A3.1 | Choose model type (ANN, SVM etc.) | 3 | A2.2 |
| A3.2 | Design model structure | 3 | A3.1 |
| A4.1 | Train model | 6 | A3.2 |
| A5.1 | Evaluate model performance | 2 | A4.1 |
| A6.1 | Develop dashboard | 33 | A5.1 |
| A7.1 | Testing and validation | 4 | A6.1 |
| A8.1 | Final report and presentation | 2 | A7.1 |

## Dependency Logic

- **A1.1** has no predecessor as it is the starting activity
- **A2.1** requires project goals to be clarified first
- **A2.2** requires raw dataset to be collected
- **A3.1** requires clean data to be available
- **A3.2** requires model type to be selected
- **A4.1** requires model structure to be designed
- **A5.1** requires trained model to be ready
- **A6.1** requires model evaluation to be complete
- **A7.1** requires working dashboard to be developed
- **A8.1** requires all testing to be completed
