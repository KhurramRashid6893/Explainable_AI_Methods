## Explainable AI: LIME & SHAP

**LIME (Local Interpretable Model-agnostic Explanations):**  
Provides **local explanations** for individual predictions by approximating a black-box model with a simple interpretable model. Works with any model.

**SHAP (SHapley Additive exPlanations):**  
Uses **Shapley values** from game theory to assign each feature a contribution to the prediction. Supports **local and global explanations** and ensures consistent, additive feature attributions.

**Key Difference:**  
LIME is **fast and local**, SHAP is **theoretically sound and global/local**.
