# Attention and driving

This is a repository holding information on papers related to attention and driving. The repository contains behavioral and practical papers published since 2010 where drivers' gaze allocation is explicitly measured (e.g. via an eye-tracker) or used in some relevant practical application.

Excluded from the list are: 

1) studies using modes of transportation other than cars (e.g. bicycles, motorcycles, trucks, buses, trains);
2) studies that rely *only* on indirect methods to assess drivers' attention (e.g. ego-vehicle sensor information);
3) studies that focused on drivers with medical issues or under the influence of alcohol or drugs;
4) uncited papers over *5* years old.


Papers in the repository are grouped into behavioral, appliation (split into 5 application categories), datasets, and other (includes surveys and other relevant papers). For each paper listed we provide citation in bibtex format and tags. For application papers we provide information on what dataset they used (*private* if data was unpublished or link to public dataset(s)). For dataset papers we provide a short summary of the dataset and available annotations.

- [Behavioral papers](behavioral.md) - theoretical analysis of drivers' attention
- Application papers - modeling or detection of drivers' attention for assistive and autonomous driving applications:
	- [Modeling scene gaze](scene_gaze.md) - models that predict where the driver might look in the traffic scene
	- [Detecting in-vehicle gaze](in-vehicle_gaze.md) - models for detecting what area inside the vehicle the driver is looking at
	- [Detecting driver distraction](distraction_detection.md) - models for detecting manual, visual, and cognitive distractions
	- [Detecting driver drowsiness](drowsiness_detection.md) - models for detecting driver drowsiness and fatigue
	- [Driver action anticipation](action_anticipation.md) - models that anticipate drivers' maneuvers using gaze and vehicle information
	- [Driver awareness estimation](driver_awareness.md) - models that project drivers' gaze onto objects in the traffic scene
	- [Attention for self-driving](self-driving.md) - models that use attention mechanisms for automated driving
	- [Papers with code](papers_with_code.md) - a list of papers across all applications that have associated code
- [Datasets](datasets.md) - a list of datasets with attention-related annotations


## Contributing to this project

If you notice any errors or missing papers and code, please post an issue on this github.

## Citation

If you used this repository in your research, please cite:

```
@article{kotseruba2022practical,
  title={Attention for Vision-Based Assistive and Automated Driving: A Review of Algorithms and Datasets},
  author={Kotseruba, Iuliia and Tsotsos, John K},
  journal={IEEE Transactions on Intelligent Transportation Systems},
  year={2022}
}

@article{kotseruba2021behavioral,
  title={Behavioral Research and Practical Models of Drivers' Attention},
  author={Kotseruba, Iuliia and Tsotsos, John K},
  journal={arXiv preprint arXiv:2104.05677},
  year={2021}
}

```

### Acknowledgment

This work is inspired by the database of papers on vision-based action prediction created by [Amir Rasouli](https://github.com/aras62/).