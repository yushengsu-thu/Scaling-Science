# Scaling-Science
In this field, researchers are devoted to pursuing scientific principles bebind scaling and use them to guide next-generation model development, where the subareas include data engineering, long context, efficiency, and science of language models. Currently, there are two primary branches of scaling science: <b>scale prediction</b> and <b>dynamic training</b>.

# Scale Prediction
- Pythia: A Suite for Analyzing Large Language Models (可復現訓練框架，開源很多checkpoint, 沒有LLMA,  dynamic) [bad]
- Predicable memorization: Emergent and Predictable Memorization in Large Language Models [bad]
- Training Trajectories of Language Models Across Scales
- Memorization Without Overfitting: Analyzing the Training Dynamics of Large Language Models


# Dynamic Training
- Unlock Predictable Scaling from Emergent Abilities (Best optimal (data:scale) ration)
- Emergent Abilities of Large Language Models (Supportive: Accuracy in some tasks [especially on unnatural in-context learning tasks. Time:5:04] suddenly breakthrough (not obey scaling-law curve), why they will suddenly emerge)
  - Emergent Abilities Definition: An ability is emergent if it is not present in smaller models but is present in larger models.

- Are Emergent Abilities of Large Language Models a Mirage? (UnSupportive: Emerging ability is from metric selection)
- Are Emergent Abilities in Large Language Models just In-Context Learning? (UnSupportive: Emerging ability is related to in-context learning)
- UNLOCK PREDICTABLE SCALING FROM EMERGENT ABILITIES (Supportive: [pass-and-tune-method] task accuracy can predict), (fixed data ratio)
- (Chinchilla) Training Compute-Optimal Large Language Models (There is an optimal ratio for data and scale on different size models.)
- - - - (Scale law prediction application: 20:57~23:30) Well-tuned a small model —> scale up to LLM
- - - - Stable training: 擴展過程中，超餐的穩定性 (試過好) : Tensor Programs V: Tuning Large Neural Networks via Zero-Shot Hyperparameter Transfer (25:00-27:00)


- Prediction Scaling (topic):
- Ability Emerge 
- Grokking: Generalization Beyond Overfitting on Small Algorithmic Dataset (33:00)
- Double Decent: https://zhuanlan.zhihu.com/p/419244046

