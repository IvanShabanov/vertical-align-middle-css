# Vertical align middle CSS

        .middle:before {
          padding: 0px;
          margin: 0px;	
          content: "";
          display: inline-block;
          min-height: inherit;
          height: 100%;
          width: 0px;
          vertical-align: middle;
        }
        .middle > * { 
          vertical-align: middle;
          display: inline-block;
        }  
