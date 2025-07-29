# Part I
## Claim 1: Uncertainty can be used in hallucination detection

## Claim 2: Uncertainty can not be reduced by incorporating more data.

## Claim3: Uncertainty in Bayesian perspective (aleatoric uncertainty)

## Claim 4: Ensemble is a way for Uncertainty Quantification.

## Challenges & Solution : 
### 1. Granularity for uncertainty measurement (from token-level to document-level).
- propose claim-level UQ.
  


# Part II (Unsupervised UQ, information-bottleneck perspective)

## uncertainty -> entropy/likelihood

## variability of using likelihood (noisy)

  ### Solution 1: claim conditional-based probability (ignore non-important words, only sensitive words)
  ### Solution 2: Monte-Carlo estimation, multi-time sampling to calculate the entropy, but requires an additional adjusted term. 
  - confusion point
### solution 3: self-consistency (frequency scoring)
- lexical similarity
- semantic entropy over a semantic cluster in which the sentences entail each other
- from hard clustering to soft clustering

### verbalized uncertainty
  prompt model to generate p(Idk)



# Part III (Unsupervised UQ, introspective)
## hidden states (the hidden states, faithful and hallucinated areas are separated) 
- Mahalanden distribution to model

- attention (LLM attends differently when generating hallucinations vs faithfully) 

# Part IV (normalize uncertainty)














