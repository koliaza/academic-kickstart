---
title: "Client-side hashing for efﬁcient typo-tolerant
password checkers"
date: 2020-09-10
authors: ["Enka Blanchard"]
publication_types: ["3"]
categories: ["preprint"]
abstract: " Credential leaks still happen with regular frequency,
and show evidence that, despite decades of warnings, password
hashing is still not correctly implemented in practice. The
common practice today, inherited from previous but obsolete
constraints, is to transmit the password in cleartext to the
server, where it is hashed and stored. This allows some usability
improvements, such as typo-tolerant password checkers — which
can correct up to 32% of typos, with no negative impact on
security — formally introduced by Chatterjee et al. in 2016, but
used in some preliminary forms since 2012.
We investigate the advantages and drawbacks of the alter-
native of hashing client-side, and show that it is present today
exclusively on Chinese websites. We then propose an alternative
typo-correction framework based on client-side hashing, which
corrects up to 57% of typos without affecting user experience,
at no computational cost to the server. Finally, we propose some
potential ways to improve the industry standards by enforcing
accountability on password security. "
featured: false
---

