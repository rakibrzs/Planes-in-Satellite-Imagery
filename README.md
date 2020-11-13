# Planes-in-Satellite-Imagery

Data - Planes in satellite imagery [Kaggle]

--Source dataset[Southern California]
--Target dataset[Northern California]

Case-1: Transfer Learning 
	[Source{train(90%),validation(10%)}, Target {test(100%)}]
	
    code: Source(s)_target(t).ipynb

Case-2: Targeted Transfer Learning [set difference]
	[Source(train+n,validation), Target (Test-n)] 
	
    code: Source(s+n)_target(t-n)[set_difference].ipynb
	
	** n is selected from target dataset 
		[that images contain interactions in the set difference]

Case-2: Targeted Transfer Learning [randomly]
	[Source(train+n,validation), Target (Test-n)] 
	
    code: Source(s+n)_target(t-n)[randomly].ipynb
	** n is selected from target dataset [randomly]

Case-3: Fine-tuning
	
    code: Fine-tuning.ipynb
