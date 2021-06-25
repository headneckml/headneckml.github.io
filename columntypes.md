colHeaders: ['<div title="description">Sex</div>',
          '<div title="description">Race</div>',
          '<div title="description">InOut</div>',
          '<div title="description">Transt</div>',
          '<div title="description">Anesthesia</div>',
          '<div title="description">Surgeon Speciality</div>',
          '<div title="description">Electsurg</div>',
          '<div title="description">Diabetes</div>',
          '<div title="description">Smoke</div>',
          '<div title="description">Dyspnea</div>',
          '<div title="description">FNStatus</div>',
          '<div title="description">Ventilat</div>',
          '<div title="description">Hypermed</div>',
          '<div title="description">Emergency</div>',
          '<div title="description">Wound Class</div>',
          '<div title="description">ASA Class</div>',
          '<div title="description">CPT</div>',
          '<div title="description">Age</div>',
          '<div title="description">HTOODAY</div>',
          '<div title="description">Height</div>',
          '<div title="description">Weight</div>',
        ],
        columns: [
          {
            data: 'sex',
            editor: 'select',
            selectOptions: ['Female', 'Male', 'N/A'],
          },
          {
            data: 'race_new',
            editor: 'select',
            selectOptions: ['American Indian or Alaska Native', 'Asian', 'Black or African American', 'Native Hawaiian or Pacific Islander', 'White', 'N/A'],
          },
          {
            data: 'inout',
            editor: 'select',
            selectOptions: ['Inpatient', 'Outpatient'],
          },
          {
            data: 'transt',
            editor: 'select',
            selectOptions: ['Admitted directly from home', 'Acute Care Hospital', 'From acute care hospital inpatient', 'Nursing home - Chronic care - Intermediate care', 'Chronic Care Facility', 'Not transferred (admitted from home)', 'Nursing home - Chronic care - Intermediate care', 'Transfer from other', 'Outside emergency department', 'Other', 'N/A'],
          },
          {
            data: 'anesthes',
            editor: 'select',
            selectOptions: ['General',],
          },
          {
            data: 'surgspec',
            editor: 'select',
            selectOptions: ['Cardiac Surgery', 'General Surgery', 'Gynecology', 'Neurosurgery', 'Orthopedics', 'Plastics', 'Vascular', 'Otolaryngology (ENT)', 'Thoracic', 'Urology'],
          },
          {
            data: 'electsurg',
            editor: 'select',
            selectOptions: ['Yes', 'No', 'N/A'],
          },
          {
            data: 'diabetes',
            editor: 'select',
            selectOptions: ['No', 'Insulin', 'Non-Insulin', 'Oral'],
          },
          {
            data: 'smoke',
            editor: 'select',
            selectOptions: ['Yes', 'No'],
          },
          {
            data: 'dyspnea',
            editor: 'select',
            selectOptions: ['AT REST', 'MODERATE EXERTION', 'No'],
          },
          {
            data: 'fnstatus2',
            editor: 'select',
            selectOptions: ['Independent', 'Partially Dependent', 'Totally Dependent', 'N/A'],
          },
          {
            data: 'ventilat',
            editor: 'select',
            selectOptions: ['Yes', 'No'],
          },
          {
            data: 'hypermed',
            editor: 'select',
            selectOptions: ['Yes', 'No'],
          },
          {
            data: 'emergency',
            editor: 'select',
            selectOptions: ['Yes', 'No'],
          },
          {
            data: 'wndclas',
            editor: 'select',
            selectOptions: ['1-Clean', '2-Clean/Contaminated', '3-Contaminated', '4-Dirty/Infected'],
          },
          {
            data: 'asaclas',
            editor: 'select',
            selectOptions: ['1-No Disturb', '2-Mild Disturb', '3-Severe Disturb', '4-Life Threat', '5-Moribund', 'None assigned', 'N/A',],
          },
          {
            data: 'cpt',
            type: 'numeric' 60220, 60240, 60252, 60254, 60210, 60225, 60212, 60260, 60270,
       60271, 60200
          },
          {
            data: 'age',
            type: 'numeric'
          },
          {
            data: 'htooday',
            type: 'numeric'
          },
          {
            data: 'height',
            type: 'numeric'
          },
          {
            data: 'weight',
            type: 'numeric'
          },
        ],