This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# Design System

This project contains some very functional, beautiful and reusable React components. Use them if you want to.

## Components

---

### Button

- **Accepted props**

  | Prop type    | Role                                            | Possible values                      |
  | ------------ | ----------------------------------------------- | ------------------------------------ |
  | **type**     | _Specifies what kind of styling to give button_ | `'primary'`, `'danger'`, `'default'` |
  | **text**     | _Any text you want written on button_           | string                               |
  | **disabled** | _If you want the button disabled or not_        | `true`, `false`                      |
  | **onClick**  | _Function to call when button is clicked_       | `function() {}`                      |

- **Screenshot(s)**

  ![Buttons](https://i.ibb.co/kg61dRN/buttons.jpg)

### Toggle

- **Accepted Props**

  | Prop type        | Role                                                                                                          | Possible values  |
  | ---------------- | ------------------------------------------------------------------------------------------------------------- | ---------------- |
  | **states**       | _An array of two items containing the texts you want in the toggle. Ignore if you want a textless toggle_     | array of strings |
  | **isOn**         | _Use a prop or state to set it's value_                                                                       | `'on'`, `'off'`  |
  | **handleToggle** | _Function that fires once toggle is clicked. Typically, you want to change the state controlling the toggle._ | `function() {}`  |

- **Screenshots**

  ![Toggle On](https://i.ibb.co/BBVJmqR/toggle-on.jpg)
  ![Toggle Off](https://i.ibb.co/wRpj2kD/toggle-off.jpg)

### Input

- **Accepted Props**

  | Prop type       | Role                                                                  | Possible values                                               |
  | --------------- | --------------------------------------------------------------------- | ------------------------------------------------------------- |
  | **type**        | _Determines the styling and acceptable input of the button_           | `'text'`, `'password'`, `'number'`                            |
  | **placeholder** | _The text you want displayed in the field until the input is entered_ | any text(However, password types do not display placeholders) |
  | **disabled**    | _If you want the input disabled or not_                               | `true`, `false`                                               |

- **Screenshots**

  ![Input Full](https://i.ibb.co/47zT6pF/input-full.jpg)
  ![Input Empty](https://i.ibb.co/gtsM6ZW/input-empty.jpg)

### Textarea

- **Accepted Props**

  | Prop type       | Role                                                                               | Possible values |
  | --------------- | ---------------------------------------------------------------------------------- | --------------- |
  | **label**       | _Appears just above the textarea, letting you know what content the textarea asks_ | any text        |
  | **placeholder** | _The text you want displayed in the field until the textarea is entered_           | any text        |
  | **disabled**    | _If you want the textarea disabled or not_                                         | `true`, `false` |

- **Screenshots**

  ![Textarea](https://i.ibb.co/2P3LMVR/textarea.jpg)

### Select

- **Accepted Props**

  | Prop type        | Role                                           | Possible values                   |
  | ---------------- | ---------------------------------------------- | --------------------------------- |
  | **options**      | _An array of options you want in the dropdown_ | any array containing string items |
  | **handleSelect** | _A function to handle selection of an option_  | `function() {}`                   |

- **Screenshots**

  ![Select](https://i.ibb.co/wdqf4MR/select.jpg)

### Modal

- **Accepted Props**

  | Prop type       | Role                                                                           | Possible values |
  | --------------- | ------------------------------------------------------------------------------ | --------------- |
  | **title**       | _Modal title_                                                                  | string          |
  | **isOpen**      | _A state or props driven value that controls whether the modal is open or not_ | `true`, `false` |
  | **handleModal** | _A function that changes the value of state or prop to control the modal_      | `function() {}` |

- **Screenshots**

  ![Modal](https://i.ibb.co/L9XBgQY/modal.jpg)

### Checkbox

- **Accepted Props**

  | Prop type          | Role                                                                                | Possible values |
  | ------------------ | ----------------------------------------------------------------------------------- | --------------- |
  | **isChecked**      | _a state or prop driven value that controls whether the checkbox is checked or not_ | `true`, `false` |
  | **handleCheckbox** | _A function that changes the value of state or prop to control the checkbox_        | `function() {}` |

- **Screenshots**

  ![Checkbox Off](https://i.ibb.co/VWvrkyH/checkbox-off.jpgg)
  ![Checkbox Off](https://i.ibb.co/pdGHNSZ/checkbox-on.jpg)

### Link

- **Accepted Props**

  | Prop type    | Role                                          | Possible values |
  | ------------ | --------------------------------------------- | --------------- |
  | **location** | _The href of the link_                        | string          |
  | **external** | _Whether the link is an external or internal_ | `true`, `false` |

- **Screenshots**

  ![Link](https://i.ibb.co/RY0FYGp/link.jpg)

### Composed Modal

- **Accepted Props**

  | Prop type               | Role                                                                                    | Possible values |
  | ----------------------- | --------------------------------------------------------------------------------------- | --------------- |
  | **title**               | _Composed Modal title_                                                                  | string          |
  | **isComposedModalOpen** | _A state or props driven value that controls whether the composed modal is open or not_ | `true`, `false` |
  | **handleComposedModal** | _A function that changes the value of state or prop to control the composed modal_      | `function() {}` |

- **Screenshots**

  ![Composable Modal](https://i.ibb.co/2cSyNHD/composable-modal.jpg)

Built by the awesome Samakintunde(Designer:paintbrush: and developer:computer:).
