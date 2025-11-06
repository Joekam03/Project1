# Project1
Understanding Uncertainty Project 1

The CSVs in the Normal and Complex directories represent 48 different patients, whose heartbeats were measured for slightly over 30 minutes.

- Patients 100-124 (23 patients) are a representative sample for routine clinical use

- Patients 200-234 (25 patients) have rare but clinically important phenomena that would not be well-represented by a small random sample of Holter recordings.

- The subjects were 25 men aged 32 to 89 years, and 22 women aged 23 to 89 years. (Records 201 and 202 came from the same male subject.)

The columns in each patient's CSV is separated into "upper" and "lower" signals

- In most CSVs, the upper signal (position of electrode on the heart) is a modified limb lead II (MLII), obtained by placing the electrodes on the chest. The lower signal is usually a modified lead V1 (occasionally V2 or V5, and in one instance V4).

- Normal QRS complexes (what looks like a heartbeat if you graph it) are usually prominent in the upper signal. Normal beats are frequently difficult to discern in the lower signal, although ectopic beats will often be more prominent (see, for example, record 106).

- A notable exception is record 114, for which the signals were reversed. Since this happens occasionally in clinical practice, arrhythmia detectors should be equipped to deal with this situation. In records 102 and 104, it was not possible to use modified lead II because of surgical dressings on the patients; modified lead V5 was used for the upper signal in these records.

Note: We haven't yet figured out what the x_mitdb folder has in it