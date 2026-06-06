# NeuraDock EEG Workstation

NeuraDock EEG Workstation is a 7-channel dry-electrode EEG development kit for researchers, developers, and makers working with brain signals.

It combines a wearable dry-electrode EEG headset, a compact acquisition module, recording software, Python tools, example workflows, and an open-source EEG analysis agent.

This repository serves as the main entry point for NeuraDock EEG Workstation developer resources.

## What It Is

NeuraDock EEG Workstation is designed to help developers and research teams prototype, record, analyze, and build applications with EEG data.

The system supports:

- 7-channel dry-electrode EEG recording
- USB and Bluetooth EEG data streaming
- Python-based EEG data reading and analysis workflows
- Example EEG experiments and signal processing demos
- Natural-language EEG analysis workflows through NeuraDock Agent
- Hardware interface and port specifications for third-party integration

## Electrode Layout

The default 7-channel electrode layout is:

- O1
- O2
- Oz
- PO3
- PO4
- CP5
- CP6

This montage is designed for occipital and parietal-occipital EEG experiments, including visual and attention-related paradigms such as SSVEP, cVEP, P300, and other EEG-based interaction prototypes.

## Repository Map

| Repository | Description | Status |
|---|---|---|
| [eeg-workstation](https://github.com/Neuradock/eeg-workstation) | Main project overview and repository navigation | Public |
| [eeg-workstation-docs](https://github.com/Neuradock/eeg-workstation-docs) | Documentation, getting started guides, data format, FAQ, troubleshooting, and hardware interface notes | Public |
| [eeg-workstation-software](https://github.com/Neuradock/eeg-workstation-software) | NeuraDock Recording Software releases and software usage notes | Public |
| [eeg-workstation-python](https://github.com/Neuradock/eeg-workstation-python) | Python tools, notebooks, and EEG data reading examples | Public |
| [eeg-workstation-agent](https://github.com/Neuradock/eeg-workstation-agent) | EEG Agent workflows, prompts, and analysis pipelines | Preparing |
| [eeg-workstation-examples](https://github.com/Neuradock/eeg-workstation-examples) | Example EEG demos, including eyes-open/closed, PSD, band power, SSVEP, cVEP, signal quality, and real-time marker workflows | Public |
| [eeg-workstation-data](https://github.com/Neuradock/eeg-workstation-data) | Public sample EEG datasets for tutorials and examples | Public |
| [eeg-workstation-hardware](https://github.com/Neuradock/eeg-workstation-hardware) | Hardware interface and port specifications for third-party integration | Public |

## Getting Started

If you are new to NeuraDock EEG Workstation, we recommend starting in this order:

1. Read the documentation and setup guide.
2. Review the EEG data format.
3. Try the Python data reading examples.
4. Run an example workflow, such as eyes-open/closed or SSVEP.
5. Explore NeuraDock Agent workflows for EEG analysis automation.

Recommended starting points:

- Documentation: [eeg-workstation-docs](https://github.com/Neuradock/eeg-workstation-docs)
- Python examples: [eeg-workstation-python](https://github.com/Neuradock/eeg-workstation-python)
- Example workflows: [eeg-workstation-examples](https://github.com/Neuradock/eeg-workstation-examples)
- Sample data: [eeg-workstation-sample-data](https://github.com/Neuradock/eeg-workstation-sample-data)
- Hardware interface notes: [eeg-workstation-hardware](https://github.com/Neuradock/eeg-workstation-hardware)

## Example Workflows

Planned and in-progress example workflows include:

| Workflow | Description |
|---|---|
| Eyes-open / eyes-closed | Basic EEG comparison workflow for signal inspection and alpha activity observation 
| Band power analysis | Frequency band power calculation and visualization | [eeg-workstation-examples](https://github.com/Neuradock/eeg-workstation-examples) |
| PSD visualization | Power spectral density visualization for EEG signals | [eeg-workstation-examples](https://github.com/Neuradock/eeg-workstation-examples) |
| SSVEP demo | Visual stimulation and offline SSVEP analysis workflow | [eeg-workstation-examples](https://github.com/Neuradock/eeg-workstation-examples) |
| cVEP demo | Code-modulated visual evoked potential demo workflow | [eeg-workstation-examples](https://github.com/Neuradock/eeg-workstation-examples) |
| Signal quality check | Basic signal quality evaluation workflow | [eeg-workstation-examples](https://github.com/Neuradock/eeg-workstation-examples) |
| Real-time marker workflow | EEG data streaming with event markers and trigger alignment | [eeg-workstation-examples](https://github.com/Neuradock/eeg-workstation-examples) |
| Visual reconstruction demo | Advanced research example based on EEG visual reconstruction workflows | [eeg-workstation-examples](https://github.com/Neuradock/eeg-workstation-examples) |

## NeuraDock Agent

NeuraDock Agent is an open-source EEG analysis agent designed to help users process EEG data through natural-language instructions.

Example tasks include:

- Loading EEG recording files
- Running preprocessing workflows
- Calculating band power features
- Generating time-frequency visualizations
- Creating signal quality summaries
- Producing analysis reports from recorded EEG data

NeuraDock Agent is not an open-source large language model. It is an open-source EEG analysis workflow layer designed to work with EEG data, tools, prompts, and analysis pipelines.

## Open Source Scope

NeuraDock is preparing open resources for EEG developers and researchers, including:

- EEG data reading examples
- Python-based analysis workflows
- Tutorial notebooks
- Example EEG experiments
- Agent workflows and prompts
- Hardware interface and port specifications for third-party integration

For hardware, the current public scope focuses on hardware interface and port specifications. Full hardware schematics, PCB design files, BOM, and manufacturing files are not included in the current public release scope.

Related repositories:

- [eeg-workstation-python](https://github.com/Neuradock/eeg-workstation-python)
- [eeg-workstation-examples](https://github.com/Neuradock/eeg-workstation-examples)
- [eeg-workstation-hardware](https://github.com/Neuradock/eeg-workstation-hardware)

## Hardware Interface Scope

The hardware-related public materials are intended to support third-party integration at the interface level.

Planned public hardware interface materials include:

- Data streaming interface notes
- USB data format notes
- Bluetooth data format notes
- Port and integration specifications where applicable

These materials are intended for developers who want to connect NeuraDock EEG data with their own software, experiments, applications, or interactive systems.

Related repository:

- [eeg-workstation-hardware](https://github.com/Neuradock/eeg-workstation-hardware)

## Applications

NeuraDock EEG Workstation is intended for research and development use cases such as:

- Brain-computer interface prototyping
- EEG-based human-computer interaction
- Visual evoked potential experiments
- Attention and cognitive-state interaction prototypes
- EEG signal processing education
- AI-assisted EEG analysis workflows
- Interactive media and neurotechnology experiments

## Links

- Website: [neuradock.com](https://neuradock.com)
- Crowd Supply: [NeuraDock EEG Workstation](https://www.crowdsupply.com/neuradock/neuradock-eeg-workstation)
- Documentation: [eeg-workstation-docs](https://github.com/Neuradock/eeg-workstation-docs)
- YouTube: [@NeuraDock](https://www.youtube.com/@NeuraDock)
- Discord: [NeuraDock Community](https://discord.gg/YdQp8puZjz)

## License

- Hardware design files: CERN-OHL-W
- Mechanical CAD files: CC BY-SA 4.0
- Software (SDK and tools): MIT License
