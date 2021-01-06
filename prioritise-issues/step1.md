Give a high priority to the following types of problems.

- **Data loss**: This can occur as a result of either data corruption or usability issues. Users entrust their data to your software. If you lose their data you violate that trust, and trust that is lost is difficult to regain.

- **Security**: This may affect the confidentiality or integrity of the software’s data, the integrity of the system where your software is running, or the availability of the service your software is providing. Such problems are often exploited by malicious individuals and can therefore result in large monetary and reputational damage. Security problems can also garner unwelcomed attention from regulatory authorities or extortionists. Consequently, sweeping security issues under the carpet is not an option.

- **Reduced service availability**: If your software is providing a service, the cost of downtime may be measured in dollars (sometimes millions of them). Lost goodwill, late-night phone calls from irate managers, and clogged support desks are additional consequences you want to avoid.

- **Safety**: These are issues that may result in death or serious injury to people, loss or severe damage to property, or environmental harm. All consequences of the preceding problems apply here. If your software can fail in such a way, you should have more rigorous processes than this list to guide your actions.

- **Crash or freeze**: This may result in data loss or downtime, and it may also signify an underlying security problem. Thankfully, you can often easily debug a crashed or non-responding application through postmortem debugging (see Item 35: “Know How to Work with Core Dumps”). Consequently, it makes little sense to give such issues a low priority.

- **Code hygiene**: Compiler warnings, failed assertions, unhandled exceptions, memory leaks, and, in general, inferior code quality provide a fertile ground for serious bugs to develop and hide. Therefore, don’t let such issues persist and accumulate (see Item 20: “Houseclean Before and After Debugging”).

The following are types of problems you may decide to relegate to a lower priority. These issues are not by themselves unworthy of your attention. However, they are issues you may be able to set aside in order to deal with more urgent ones.

- **Legacy support**: Support for outdated hardware, API, and file formats is commendable, but, from a business perspective, it won’t get you very far because, by definition, you’re serving a shrinking market.

- **Backward compatibility**: Here the case is less clear-cut because if your software evolves in a way that leaves behind past users, you’re losing customer goodwill. Some companies, such as Nikon, have established a stellar reputation by maintaining backward compatibility through many generations of their product: you can still use a 1970s Nikkor lens on high-end modern Nikon cameras. On the other hand, some successful software firms are known for their “take no prisoners” approach, where they ditch support for older software and services without any qualm. Sometimes it may be worth eliminating support for an old feature in order to focus on the future.

- **Cosmetic issues**: These may be devilishly hard to get right and easy to ignore. You are unlikely to lose business over a truncated bubble-help item, but dynamically adjusting the size of the item’s panel based on the screen’s dpi setting can be a nightmare.

- **Documented workarounds**: You may be able to avoid debugging some tricky issues by documenting a workaround. After switching on my TV, the first time I try to use the TV’s remote to operate the media player I get a “Please try again” prompt. I suspect that properly fixing this minor problem may be a major project.

- **Rarely used features**: For problems associated with an exotic, rarely used feature of your software, it may be more productive to yank the corresponding feature (and deal with the small, if any, fallout), than to actually solve the problem. Collecting usage data regarding your software can make it easier for you to reach such decisions.