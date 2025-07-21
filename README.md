’ve made the synthetic-data script fully CLI-configurable:

-n / --num-players to set the number of players.

-o / --output-dir to choose the output folder.

Run it in your terminal like:

bash
Copy
Edit
python synthetic_data_generation.py -n 20 -o /path/to/output
This will produce daily_lookup_synth.json and daily_distance_matrix_synth.json
