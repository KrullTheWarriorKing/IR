---
hide:
  -toc
  -navigation
---


<html>
<head>
<link rel="stylesheet" href="../_css/form.css" />
</head>

<body>
<div class="container">
		<header class="header">
			<h1 id="title" class="text-center">
				Prendre contact
			</h1>
			<p id="description" class="description text-center">
			</p>
		</header>   
		<form id="survey-form" action="https://formspree.io/f/xnqrqwpo" method="POST">	
			<div class="form-group">
				<label id="name-label" for="name">
					Prénom et NOM
				</label>
				<input type="text" name="name" id="name" class="form-control" placeholder="Enter your name" required/>
        		</div>
			
			<div class="form-group">
				<label id="email-label" for="email">
					Email
				</label>
				<input type="email" name="email" id="email" class="form-control" placeholder="Enter your Email" required/>
			</div>
			
			<div class="form-group">
				<label id="number-label" for="number" >
					Age
					<span class="clue">
						(optional)
					</span>
				</label>
				<input type="number" name="age" id="number" min="10" max="99" class="form-control" placeholder="Age" />
			</div>
			
			<div class="form-group">
				<p>
					Which option best describes your sexual orientation?
				</p>
				<select id="dropdown" name="role" class="form-control" required>
					<option disabled selected value>
						Select Sexuality
					</option>
					<option value="Gay">
						Gay/Lesbian/Homosexual/Homoromantic
					</option>
					<option value="Bi">
						Bisexual/Pansexual/Omnisexual
					</option>
					<option value="Queer">
						Sexually-Fluid/Queer
					</option>
					
					<option value="Questioning">
						Unsure/Questioning
					</option>
										
					<option value="preferNo">
						Prefer not to say 
					</option>
					
					<option value="other">
						Other
					</option>
					<option value="Asexuality">
						Asexuality / Aromantic (Spectrum)
					</option>
				</select>
			</div>

			<div class="form-group">
				
				<p>
					Do you have any friends who are not explicitly cisgender & heterosexual?
				</p>
				
				<label>
					<input name="user-recommend" value="definitely" type="radio" class="input-radio" checked />
					Yes
				</label>
				
				<label>
					<input name="user-recommend" value="maybe" type="radio" class="input-radio" />
					Maybe
				</label>

				<label>
					<input name="user-recommend" value="not-sure" type="radio" class="input-radio" />
					No
				</label>
			</div>

			<div class="form-group">
				<p>
					What is your gender identity?
				</p>
			
				<select id="most-like" name="mostLike" class="form-control" required>
					
					<option disabled selected value>
						Select an option
					</option>
					
					<option value="Woman">
						Woman (Trans or Cis)
					</option>
					
					<option value="Man">
						Man (Trans or Cis)
					</option>
					
					<option value="NB">
						Non-Binary
					</option>
					
					<option value="Intersex">
						Intersex
					</option>
					<option value="Regional Gender">
						Regional Gender (Two-Spirit/Hijra/Kathoey)
					</option>					
					<option value="Agender">
						Agender (Agender Spectrum)
					</option>
					<option value="Combination">
						Combination of Above
					</option>
					<option value="Not Mentioned">
						Not Mentioned Here/Questioning
					</option>
					<option value="Prefer not to say">
						Prefer not to say
					</option>					
				</select>
			</div>
			
			<div class="form-group">
				<p>
					Any comments or suggestions?
				</p>
				
				<textarea id="comments" class="input-textarea" name="comment" placeholder="Enter your comment here...">
				</textarea>
			</div>
			
			<div class="form-group">
				<button type="submit" id="submit" class="submit-button">
					Submit
				</button>
			</div>
		</form>
	</div>
	</body>
</html>


<br> 

<style>
  .md-content__button {
    display: none;
  }
</style>
