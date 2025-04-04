## About

To facilitate research on the effects of opioid withdrawal on sleep, researchers at Harvard Medical School, McLean Hospital, and Brigham & Women's Hospital have released the rat oxycodone withdrawal dataset featured in Gulledge et al. PLOS One. This dataset comprises electroencephalography (EEG) and electromyography (EMG) recordings obtained from male Sprague Dawley rats. The data were collected during an experiment aimed at establishing a comprehensive, temporal signature of spontaneous oxycodone withdrawal effects on sleep-wake cycles and dynamic spectral properties of the EEG in male rats. The dataset includes EEG, EMG, activity counts, and temperature data. Rats were administered either an escalating dose of oxycodone over a 14-day period or a corresponding dose of saline as a control.

## Methods

Rats were implanted with iPrecio pumps that were programmed to infuse either saline or oxycodone twice a day for two hours each at ZT0-2 and ZT12-14. For the first several days after surgery, pumps infused 0.9% saline (days 4-6). Telemetry data from these days of saline infusions were used as baseline. 

Following baseline, saline was removed from the pumps and replaced with oxycodone (0.5mg/kg). The timeline for escalating oxycodone doses included a total of 28 oxycodone infusions (ZT0-2 and ZT12-14 each day). On oxycodone day 1 (Oxy d1), rats received saline in the morning (ZT0-2) and oxycodone (0.5 mg/kg) in the evening (ZT12-14). On the last drug day, Oxy d15, rats received oxycodone (8.0 mg/kg) in the morning (ZT0-2) and no infusion in the evening (ZT12-14). Between Oxy d1 and Oxyd15, rats received 24 additional infusions of oxy (0.5 mg/kg), 6 infusions of oxy (1.0 mg/kg), 6 infusions of oxy (2.0 mg/kg), 6 infusions of oxy (4.0 mg/kg), and 5 infusions of oxy (8.0 mg/kg), with the 6th oxy (8.0 mg/kg) infusion occurring on Oxy d15 (ZT0-2). 

For all cohorts except cohort 2, infusions were delivered at rates of 15ul/h (30 ul infused) for the first 4 infusions and 30μl/h (60 ul infused) for all remaining infusions. Cohort 2 received saline during baseline and the oxy 0.5mg/kg infusions at 7.4ul/hr, oxy 1.0mg/kg at 14.8ul/hr and all remaining infusions at 29.8ul/hr. Separate rats received saline throughout the 14-d pump delivery regimen and served as controls.

The first cohort of rats (N=3) missed the first two oxycodone 0.5mg/kg infusions and received two extra infusions of saline instead. However, they received the rest of the scheduled 26 escalating oxycodone infusions: 2 infusions of oxy 0.5mg/kg, 6 infusions of 1mg/kg, 6 infusions of 2mg/kg, 6 infusions of 4mg/kg, and 6 infusions of 8mg/kg.

## Data overview

Data is provided for baseline (days 4-6), one day of 8mg/kg oxycodone or the saline equivalent (day 20) and for seven days of withdrawal (Day 22-28). During the "withdrawal period" saline control rat data is provided only for days 22, 24, 26 and 28.  Anesthetized rats were implanted with the wireless contained telemetry device, with 4 biopotential leads: 2 EMG leads that comprise one EMG channel and 2 EEG leads that comprise one channel. For each implant, the EMG leads were threaded through the cervical trapezius muscle via a small incision made with a 20-gauge needle and was anchored to the muscle using non-dissolvable silk sutures. The EEG leads were individually secured to two skull screws (Plastics One, cat #00–80 x 1/16; 1.6mm long) that contacted dura. The negative EEG lead was secured to the screw at +2.0mm anteroposterior and at lateral left 1.5mm, and the positive EEG lead was secured to the screw at -7.0mm anteroposterior and lateral right -1.5mm–all relative to Bregma. The screw plus lead assemblies were held in place on the skull with dental cement (Ortho-Jet Package; Lang Dental).

### Oxy (N=11) OR Saline (N=4)

EDF files exported by Neuroscore (Data Science International, St. Paul, MN) which include one EEG channel and one EMG channel. EEG and EMG data were recorded at an interpolated sampling rate of 500Hz.

### Sleep Scoring and Behavioral Data/Sleep Staging/Oxy (N=11) OR Saline (N=4)

CSV files containing the manually scored sleep data from the experiment. A "5" denotes Wake, "4" denotes REM, and "3" denotes NREM sleep. (double check)

### Sleep Scoring and Behavioral Data/Temperature and Activity/Oxy (N=11)

CSV files containing the average temperature reading (In Celsius) and summed Activity counts for each 10s bin (please ignore the row 2 headers). Data is provided only for the rats that received oxycodone for each day that was manually scored.

## Access and usage restrictions

The Gulledge 2025 dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)
> 
> [Gulledge M, Carlezon WA Jr, McHugh RK, Kinard EA, Prerau MJ, Chartoff EH. Spontaneous oxycodone withdrawal disrupts sleep, diurnal, and electrophysiological dynamics in rats. PLoS One. 2025 Jan 17;20(1):e0312794. doi: 10.1371/journal.pone.0312794. PMID: 39823427; PMCID: PMC11741586.](https://pubmed.ncbi.nlm.nih.gov/39823427/)

Users must include the following text in any Acknowledgements:

> The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Changelog

*April 2025*

- Make Gulledge 2025 dataset available for data requests

## References

-	Gulledge 2025 GitHub Documentation: https://github.com/nsrr/gulledge-2025-documentation

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
