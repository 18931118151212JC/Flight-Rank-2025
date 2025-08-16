# Flight Rank 2025 Competition model

This is my notebook that was used to rank the offered flights on [FlightRank 2025: Aeroclub RecSys Cup](https://www.kaggle.com/competitions/aeroclub-recsys-2025). This repository also contains a pretrained ranker, 
which is trained on 5 passes through a enormous training dataset (In code the training is splitted since otherwise data is hits over 30 GB kaggle RAM limitation). Trained for 7 hours with kaggle GPU accelerator. Added extra features include tweaked time (turning time to ordinal format and extracting specific hour, day and month)
as well as if the flight is overnight and number of layovers
