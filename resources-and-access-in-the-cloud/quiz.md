
# Google Cloud Fundamentals: Core Infrastructure

## Quiz: Resources and Access in Google Cloud

### 1. Which statement best describes how Google Cloud resources are associated within the resource hierarchy?

- [ ] All Google Cloud resources are associated with an organization.
- [ ] Google Cloud resources are not associated with the resource hierarchy.
- [ ] All Google Cloud resources are associated with a folder.
- [x] All Google Cloud resources are associated with a project.


### 2. Your company has two Google Cloud projects and you want them to share policies. What is the least error-prone way to set this up?

- [ ] Create shared resource policies on the common resources that are used in both projects.
- [ ] Define the new shared policy in the organization node.
- [x] Place both projects into a folder, and define the policies on that folder.
- [ ] Duplicate all the policies from one project onto the other.


### 3. Consider a single hierarchy of Google Cloud resources. Which of these situations is possible? (Choose 3 responses.)

- [x] There is an organization node, and there are no folders.
- [ ] There are two or more organization nodes.
- [x] There is an organization node, and there is at least one folder.
- [ ] There is no organization node, but there is at least one folder.
- [x] There is no organization node, and there are no folders.


### 4. When would you choose to have an organization node? (Select two)

- [x] When you want to centrally apply organization-wide policies
- [ ] There’s no choice; organization nodes are mandatory.
- [ ] When you want to organize resources into projects.
- [x] When you want to create folders


### 5. How does the resource hierarchy control how IAM policies are inherited?

- [ ] IAM policies are only implemented at the project level; they cannot be amended by lower levels of the resource hierarchy.
- [x] IAM policies that are implemented by lower-level policies can override the policies defined at a higher level.
- [ ] IAM policies that are implemented higher in the resource hierarchy deny access that is granted by lower-level policies.


### 6. Which way of accessing Google Cloud lets you control services through the code you write?

- [x] APIs
- [ ] The Cloud Console mobile app
- [ ] The Cloud SDK and Cloud Shell
- [ ] The Cloud Console


### 7. Select the option that displays IAM roles from general to specific.

- [ ] Predefined roles, custom roles, basic roles
- [ ] Custom roles, predefined roles, basic roles
- [x] Basic roles, predefined roles, custom roles


### 8. What is the difference between Identity and Access Management (IAM) basic roles and IAM predefined roles?

- [ ] Basic roles only apply to the owner of the Google Cloud project. Predefined roles can be associated with any user.
- [ ] Basic roles can only be granted to single users. Predefined roles can be associated with a group.
- [ ] Basic roles only allow viewing, creating, and deleting resources. Predefined roles allow any modification.
- [x] Basic roles affect all resources in a Google Cloud project. Predefined roles apply to a specific service in a project.

