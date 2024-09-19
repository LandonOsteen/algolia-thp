# Responses to Customer Issues & Questions

## Answer 1 - Dashboard Design Frustration

Hi Marissa,

Thank you for your feedback. I'm sorry to hear that the new dashboard design is causing you frustration. I understand how important it is to have quick access to the features you need while iterating. We are currently reviewing the layout and will prioritize making these features easier to reach in upcoming updates. In the meantime, I'll see if there are any workarounds we can offer. Thanks again for sharing your thoughts, and we'll aim to improve the experience soon!

Best regards,

**Landon Osteen**

Algolia Customer Success Engineer

## Answer 2 - Metadata Issue

Hi Carrie,

Thanks for reaching out, and I'm sorry to hear about the issue! The error you're seeing ("Record is too big") happens when the size of the record exceeds the limits set by Algolia. Given that you're enriching records with a lot of metadata, it’s likely that some records are larger than the allowed size.

To fix this issue, you can:

- Trim the amount of metadata added to each record that isn't necessary for search.
- Consider splitting large records into multiple smaller ones, focusing on what's needed for search and omitting or storing metadata elsewhere.
- If metadata is still required, it can be linked or stored in another system rather than within the records themselves.

Let us know if you'd like help with these changes or need additional support to resolve the problem.

Best,

**Landon Osteen**

Algolia Customer Success Engineer

## Answer 3 - Missing Dependency

Hi Marc,

Thanks for sending over the error. It looks like the issue might be related to a missing dependency in your website's code, specifically the searchkit package. This can happen if the package wasn’t installed correctly or referenced properly in your project.

Here's a quick fix you can try:

- Ensure that searchkit is included in your package.json dependencies.
- Run npm install searchkit to install it if it’s missing.
- After installation, restart your development server with npm start or yarn start.

If the issue persists, feel free to send me more details, and I’ll look into it further!

Best regards,

**Landon Osteen**

Algolia Customer Success Engineer
