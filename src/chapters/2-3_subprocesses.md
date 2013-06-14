Sub-processes of the software development process
-------------------------------------------------


As said previously on this document,

> A *software development methodology*, in relation to *sub-processes*, is a
> convention on how they are arranged to develop the *software product*.

Let's identify the common concepts widely used to refer those sub-processes,
abstractly speaking, prior to define the proposed development methodology,
consisting of a mix of the key existing agile methodolgies.


**WARNING: this enumeration still needs some serious work**

- **Planing**: During this sub-process the primary task is define the *objectives*. Objectives are the features the software must have.

- **Analysis**: Given an objective, the goal is define the software requirements to accomplish it. To do that, analysts must keep in consideration the user types and its access limits to the app. This sub-process transforms *objectives* into *requirements*.

- **Design**: Given a *requirement*, it's the moment to design how it's going to be implemented. Depending on the feature, several sub-processes are performed, each one producing as result different kind of *design(s)*.

    - **Content design**: The action of designing the way the data will be managed.

        - **Definition and categorization of contents**: Produces *sitemap(s)*.
            - **see**
                - Semantic web - http://schema.org/
                - book: Information Architecture for the World Wide Web - O'Reilly

        - **Data model design**: Where Information Architecture matters.
            - **Conceptual design**: produces *schema(s)*?.
            - **Logic design**: The implantation of the database itself, based on *schemas*.

    - **Visual design**: The action of designing the *User Interface (UI)*. This process implies several sub-processes:

        - **Wireframing**: The action of sketching the UI.
        - **Iterations design**: The action of designing how the UI responds to the user input.
        - **Graphics design**: The action of transform the *wireframes* into a graphic design through art, the final appearance of the UI.

- **Implementation**: The writing of the code itself. On web development, *back-end* refers to the server-side code, while *front-end* refers to the client-side code. *Full-stack* refers to the whole application code. This sub-process transforms *designs* onto *features*.

- **Test, Verification or Evaluation**: This process ensures that the *features* meet the *requirements*. 
- **Deploy**: The action of deliver the software to the client.
- **Upkeep and Optimization**: This sub-process includes the tasks related to bug fixes and improvements on appearance or performance. 
