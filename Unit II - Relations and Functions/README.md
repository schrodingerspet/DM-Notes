# Unit II - Relations and Functions

## ✦ Syllabus:
> - Relations and their Properties
> - n-ary relations and their applications
> - Representing relations
> - Closures of relations
> - Equivalence relations
> - Partial orderings
> - Partitions
> - Hasse diagram
> - Lattices
> - Chains and Anti-chains
> - Transitive closure and Warshall's algorithm
> - Functions:
>   - Surjective
>   - Injective and Bijective functions
>   - Identity function
>   - Partial function
>   - Invertible function
>   - Constant function
>   - Inverse functions and compositions of functions
>   - The pigeonhole principle

---

## ✦ Relations and Functions

### Relations and Their Properties:
- A relation \( R \) from set \( A \times B \) is a subset of \( A \times B \)
- \( R_{\text{max}} = A \times B \)
- \( R_{\text{min}} = \emptyset \)
  
![image](https://user-images.githubusercontent.com/68887544/116503631-332c3380-a8d4-11eb-825f-35d7005e2095.png)

---

### Representation of Relations:
- Relation as Matrix:
  ![image](https://user-images.githubusercontent.com/68887544/116504103-3c69d000-a8d5-11eb-9def-8ef24bbf662b.png)
- Relation as a Directed Graph (Digraph):
  ![image](https://user-images.githubusercontent.com/68887544/116504256-805cd500-a8d5-11eb-8cc3-6a15933ec1a0.png)
- Relation as an Arrow Diagram:
  ![image](https://user-images.githubusercontent.com/68887544/116504376-c0bc5300-a8d5-11eb-99d6-3fc74440c09b.png)
- Relation as a Table:
  ![image](https://user-images.githubusercontent.com/68887544/116504515-1133b080-a8d6-11eb-82dd-7c719698f537.png)

---

### Binary Relations:
- A binary relation \( R \) is a subset of \( P \times Q \) from set \( P \) to \( Q \).
  ![image](https://user-images.githubusercontent.com/68887544/116504677-81423680-a8d6-11eb-85ab-9ef01e8d5d03.png)

---

### Domain of a Relation:
- The first entry in an ordered pair of \( R \).
- \( \text{Dom}(R) = \{\text{elements}\} \)
  ![image](https://user-images.githubusercontent.com/68887544/116504785-c8302c00-a8d6-11eb-9178-429c0daa07ce.png)

---

### Range of a Relation:
- The second entry in an ordered pair of \( R \).
- \( \text{Ran}(R) = \{a.b\} \)
  ![image](https://user-images.githubusercontent.com/68887544/116504883-104f4e80-a8d7-11eb-8310-278830aad97f.png)

---

### Types of Relations:
- **Reflexive:** Every element is related to itself.
  ![image](https://user-images.githubusercontent.com/68887544/116508038-1dbc0700-a8de-11eb-8636-be1b2d84d4a9.png)
- **Irreflexive:** No element is related to itself.
  ![image](https://user-images.githubusercontent.com/68887544/116509168-78eef900-a8e0-11eb-92b0-c3be6182ab20.png)
- **Symmetric:** If \( aRb \), then \( bRa \).
  ![image](https://user-images.githubusercontent.com/68887544/116514261-6973ae00-a8e8-11eb-8dfa-7f28a3ddcdd4.png)
- **Antisymmetric:** If \( aRb \) and \( bRa \), then \( a = b \).
  ![image](https://user-images.githubusercontent.com/68887544/116656295-0cd8c780-a9aa-11eb-8710-a2b8ca199474.png)
- **Transitive:** If \( aRb \) and \( bRc \), then \( aRc \).
  ![image](https://user-images.githubusercontent.com/68887544/116657991-ef592d00-a9ac-11eb-9ac9-d58df029f412.png)

---

### Equivalence Relations and Partial Orders:
- **Equivalence Relation:** Reflexive, symmetric, and transitive.
  ![image](https://user-images.githubusercontent.com/68887544/116659886-e0c04500-a9af-11eb-85b1-5a139ccb0321.png)
- **Partial Order:** Reflexive, antisymmetric, and transitive.
  ![image](https://user-images.githubusercontent.com/68887544/116660494-bde26080-a9b0-11eb-9cc3-96185268c103.png)

---

### Hasse Diagram:
- Simplified representation of partial order.
  ![image](https://user-images.githubusercontent.com/68887544/116675297-4d910a80-a9c3-11eb-85cb-8f94f4e9ede6.png)

---

### Lattices:
- **Lattice:** A partially ordered set where every two elements have a unique supremum (join) and infimum (meet).
  ![image](https://user-images.githubusercontent.com/68887544/116689567-ed579400-a9d5-11eb-8c5b-91b137a45520.png)
- **Join Semi-Lattice:** Set closed under join.
  ![image](https://user-images.githubusercontent.com/68887544/116688561-82598d80-a9d4-11eb-8e60-3d139572d1dc.png)
- **Meet Semi-Lattice:** Set closed under meet.
  ![image](https://user-images.githubusercontent.com/68887544/116688958-1166a580-a9d5-11eb-94a6-f8d2acf9a827.png)

---

## ✦ Functions:

### Types of Functions:
- **Injective Function:** Every element of the domain is mapped to a unique element of the codomain.
  ![image](https://user-images.githubusercontent.com/68887544/116707094-ea679e00-a9eb-11eb-93a9-df124dc90153.png)
- **Surjective Function:** Every element of the codomain has at least one pre-image in the domain.
  ![image](https://user-images.githubusercontent.com/68887544/116707586-7974b600-a9ec-11eb-9c9d-d4350f33fb5f.png)
- **Bijective Function:** Function that is both injective and surjective.
  ![image](https://user-images.githubusercontent.com/68887544/116707851-bfca1500-a9ec-11eb-8d7a-fd62c982e7b9.png)

---

### Inverse Functions and Compositions:
- **Inverse Function:** A function that "reverses" another function.
  ![image](https://user-images.githubusercontent.com/68887544/116711712-be9ae700-a9f0-11eb-931a-93a73607c1d6.png)

---

### Pigeonhole Principle:
- If \( n \) objects are placed into \( m \) containers, and \( n > m \), then at least one container must contain more than one object.
  ![image](https://user-images.githubusercontent.com/68887544/116...)
