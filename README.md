
# Epidemic Modelling

Epidemic models based on ordinary differential equations (ODEs), which effectively describe dynamic systems in many fields, have been employed. However, a single epidemic model is not enough to capture long-term dynamics of epidemic events especially when the dynamics heavily depend on external factors (e.g., lockdown and the capability to perform tests).
All These models divide the population into several compartments and capture patterns of dynamic changes in the sizes of the compartments over time. The dynamics are expressed as predefined ODEs, which are based on human knowledge, with tunable parameters. While these models are intuitive and simple, they often have limited expressiveness, failing to capture epidemic dynamics accurately. On the other hand, data-driven models aim to model and forecast co-evolving time-series data using ODEs, without relying on human knowledge. They employ latent variables and non-linear differential equations to capture complicated temporal dynamics.
Despite the development of epidemic models, describing long-term dynamics of epidemics using a single epidemic model often faces limitations due to the unpredictability and abruptness of real-world events. Indeed, various external factors may substantially change the dynamics of epidemic events. For example, policies reducing contacts between individuals (e.g., lockdown) and the capability to perform tests can significantly affect the dynamics.

# SIR Model 

SIR Model
The set of dependent variables counts people in each of the groups, each as a function of time:

S = S(t)
is the number of susceptible individuals,

I = I(t)
is the number of infected individuals, and

R = R(t)
is the number of recovered individuals.

## Screenshot
![7_1B5iBk0ewW7K3K-pI2Ohw8Cg_qtMMSMq9r0yCZt_xx7hnbZ4jna_3HGlrMiYPS_4TR_4kBQwX8Uba4JIjLA1rNOHCMGp0XnCXdIyBI-93D8jK9HHcm1SqmPIUP](https://user-images.githubusercontent.com/118846871/210311178-409f8068-6f61-4173-ad6e-28a625da17f6.png)

## Conclusion

*Fewer people end up getting the disease. Maximum infected people w.r.t time is much lower. This is flattening the curve.

-However, The model may not predict the exact absolute analysis, but it will work depending upon the integrated factors.

- We see the strong rapid peak in the epidemic, followed by decaying oscillations to the final endemic state.

- Eventually, these oscillations disappear, and the system settles in to the stable endemic equilibrium.

- The most characteristic feature of this system is the existence of two very different time scales -- the short time scale of a single epidemic, and the long generational time scale on which susceptible are replenished.

- Once the endemic state is established, any small perturbations which occur will be damped oscillations, with frequency and damping rate.
